# Quilt Installer Native Launch 

This folder contains the rust project used to launch the installer on Windows and macOS.

If the installer is run on a machine without a suitable JRE, then an error dialog will be displayed and opening a link
to help the user install a suitable JRE.

Linux will receive a special launch process in the future which will be architecture and distro agnostic for publishing
on package managers, hence not using this rust project.
