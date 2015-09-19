# *<p align="center">Installation of Mupel on your system</p>*
[<img src="../icons/back-button.png" alt="Back" width="100" height="40">](readme.md) 

-------------

For installation of Mupel is a Debian or Ubuntu 64 bit x86 system required. This is to have the needed dependencies for
them on known distributions. 64bit is needed to have full functionality there and also for a 32bit build.

Everything except the Linux x86 system becomes installed on user home folder, this does not match the "Filesystem
Hierarchy Standard", but prevent access problems where normally a super user is needed.

Also must be the source of them somewhere on the home folder!

### Table of Contents
 - [General](#general)
 - [Start of installation](#start-of-installation)
  - [Linux x86 system](#linux-x86-system)
 - [Remove installed Mupel](#remove-installed-mupel)

-------------
### General
<table>
    <dt><b>Used parts on file system as example of installed Mupel: </b></dt>
    <dd><sub><i>(changes from installed dependencies are not below)</i></sub></dd>
    <thead>
        <tr>
          <th><sub>Own Installed places:</sub></th>
          <th><sub>Description:</sub></th>
        </tr>
    </thead>
    <tr>
        <td>e.g. $HOME/mupel/...</td>
        <td>Mupel itself</td>
    </tr>
    <tr>
        <td>$HOME/.mupel/...</td>
        <td>Settings and emulation sytems</td>
    </tr>
    <tr>
        <td>/var/lib/chroot/vivid64/...</td>
        <td>Ubuntu Linux system accessed by chroot system</td>
    </tr>
    <thead>
        <tr>
          <th><sub>Changed basesystem parts:</sub></th>
          <th></th>
        </tr>
    </thead>
    <tr>
        <td>/etc/schroot/...</td>
        <td>To allow chroot access for the installed build distribution on Linux</td>
    </tr>
    <tr>
        <td>/var/lib/chroot/...</td>
        <td>Where the build systems for Linux becomes installed</td>
    </tr>
    <tr>
        <td>/etc/fstab</td>
        <td>For emulation systems are there bind mount point added</td>
    </tr>
</table>

-------------
### Start of installation

#### Linux x86 system
Linux x86 system with 64 bit is the minimum required system for the use Mupel. It is based upon a [Debian](https://en.wikipedia.org/wiki/Debian) Linux operating system and distribution and can be easily used on [Ubuntu](https://en.wikipedia.org/wiki/Ubuntu_(operating_system)).

If related parts are installed also the use of 32 bit of them is possible, which allow build tests on Kodi and to create binary packages from CEF.

Open [Linux x86 installation guide](install/install-linux.md) for detailed instructions for installation of them.

-------------
### Remove installed Mupel

-------------
*<p align="center">![Work in progress](http://img.shields.io/badge/work_in-progress-lightgray.svg)</p>*
