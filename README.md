virtualboxautodebian
====================

This is a Bash program written to auto installaiton of Virtualbox 4.3.x with PHPVirtualbox for Debian 7

The script works on a fresh installation of Debian 7.x 64 Bit Operating System.

Feature:

    Installs on a fresh Debian Wheezy machine
    Run as a root user
    Installs Virtualbox 4.3 with DKMS kernel
    Installs PhpVirtualbox web interface to control web based Virtualbox Administration

How to Install:

    login to terminal.
    su or login as root, because you need to run the script as root user
    copy the installation file to /root directory
    use "chmod+x" to virtualboxinstaller.sh
    issue command "./virtualboxinstaller.sh"
    Auto installaiton beging
    Follow on screen messages and enter different parameters as appears to complete the installtion

Known Issue:

    vbox user password is symbol sensitive which means, special characters such as \/@#$% are not supported.
