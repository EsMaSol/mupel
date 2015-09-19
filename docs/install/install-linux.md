# *<p align="center">Installation of Linux x86 build systems</p>*
[<img src="../../icons/back-button.png" alt="Back" width="100" height="40">](../readme.md) 

-------------

For the x86 build system are all currently from [Debian](https://en.wikipedia.org/wiki/Debian) or 
[Ubuntu](https://en.wikipedia.org/wiki/Ubuntu_(operating_system)) based Linux operating system and distribution 
available.

<b><i>Note:</i></b> This systems are not a normal Distribution install. It is used to allow use of others without an complete
reinstallation and this become accessed from the base only with the chroot system and easily done with a call like
<b>utopic64</b> which change to utopic on 64 bit base inside console.

Minimum one system is required for the usage of Mupel but if more as one is present can it be selected with the
settings of them.

Here comes a detailed help instructions about the installation of the build Distribution.

The installation script is present on <b>./mupel/tools/linux/install-systembuild-linux</b> which becomes called from 
the global installation <b>./mupel-install</b> and can also be called alone, further is inside Mupel itself after
installation of them a button present to open it again for changes.

The installer allow to add, update, reset or remove the selected build distributions.

*<p align="center">![Help Image 1](linux-help-1.png)</p>*

--------------

If you become after start the following message dialog, is the selected Distribution still active. 
*<p align="center">![Help Image 2](linux-help-2.png)</p>*

In this case check
your system that no where is active. On console you have always the name on begin. If yes type only exit and is
leaving chroot then.
*<p align="center">![Help Image 3](linux-help-3.png)</p>*
In the case it brings it without active chroot becomes it psooble to have a before wrongly removed access (e.g.Power Reset)

