Patch files for building Gentoo's vmware-modules-279.3 package on Linux kernel 4.0.4.

Makes the package compile without errors and allows vmware-player to run.
Use at your own risk.

Instructions:
- Clone the repository or download the files individually, manually.
- In a terminal, place the patch files in the folder where Portage looks for them:

    sudo mkdir -p /etc/portage/patches/app-emulation/vmware-modules-279.3
    
    sudo cp folder_containing_patch_files/* /etc/portage/patches/app-emulation/vmware-modules-279.3

- Re-emerge the package

    sudo emerge -av vmware-modules-279.3
