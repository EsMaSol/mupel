# *<p align="center">Mupel </p>*
#### *<p align="center">Kodi's multiplatform build environment system on Linux</p>*
*<p align="center">![alt tag](https://raw.githubusercontent.com/EsMaSol/mupel/master/icons/icon-mupel-128x128.png)</p>*

###### *<p align="center">Now you can do "<i>Èngem e' Mupel mâchen</i>" (Luxembourgish) and means "Someone squeezing the cheeks" in respect to Jenkins the best multi platform background system on world.</p>*

-------------
### *<p align="center">[Wiki](https://github.com/EsMaSol/mupel/wiki)</p>*
*<p align="center">![Work in progress](http://img.shields.io/badge/work_in-progress-lightgray.svg)</p>*

Below is a list of parts on Mupel which becomes improved, checked, added or fixed. It is a currently usable but far away from them what I want.

Steps to do:
- [ ] Rework installation
  - [ ] All build systems ready
    - [x] Rework Linux distribution install
      - [ ] Check install for all active distributions
    - [ ] Rework Raspberry build amd emulation system install
    - [ ] Rework Windows install
    - [ ] Rework Mac OS X install
    - [ ] Rework Android install
    - [ ] Rework iOS install
  - [ ] Install and usage on all debian based OS systems OK (Debian, ubuntu, Kubuntu, Lubuntu, ...)
- [ ] Add help documentation (work in progress)
- [ ] Add more git support parts
    - [ ] View of present pull requests and direct build of them
    - [ ] Add base system repositories always in which can be then selected by a check button
    - [x] Switch to source base repositories on CEF and Kodi by check button
- [ ] Rework/Add CEF build (build, not related to system install)
  - [ ] All CEF build systems ready
    - [x] Creation Linux static package OK
    - [ ] Creation Raspberry static package OK
    - [ ] Creation Windows static package OK
    - [ ] Creation Mac OS X static package OK
    - [ ] Creation Android static package OK
    - [ ] Creation iOS static package OK
  - [ ] Include complete build for all systems (currently missing)
- [x] Rework/Add Kodi build (build, not related to system install)
  - [ ] All Kodi build systems ready
    - [x] Creation Linux static package OK
    - [x] Creation Raspberry static package OK
    - [x] Creation Windows static package OK
      - [ ] Improve Windows to allow selected step build
    - [x] Creation Mac OS X static package OK
    - [x] Creation Android static package OK
    - [x] Creation iOS static package OK
  - [ ] Include complete build for all systems (currently missing)
- [ ] Add user selectable build script support

-------------
### Description
This repository contains a application system to allow build of kodi on all supported system by hand and to do quik
checks and updates during development on other OS systems.

Also support it build of all for Chromium Embedded needed parts which are complete required for the kodi web add-on. Normally are own already created binaries from web used to give it as lib and to create add-on with them, this are different from the normal ones to match Kodi's directory style and few changes on CEF are required.

The scripts here are used to create the binary libraries for the add-ons in a automatic mode for several different
systems.

-------------
Inside is a small reworked version of CEF becomes used from https://github.com/kodi-web/cef which use the Kodi.
related changes in the source code of CEF. Also contains this a needed patch for Google Chromium.

General description of CEF can be found here on [wikipedia](http://en.wikipedia.org/wiki/Chromium_Embedded_Framework).

#### *<p align="center" style="color:red">WARNING: This app need a ubuntu or debian 64bit system as base!<p>*

-------------
[Documentation](https://github.com/EsMaSol/mupel/wiki) - Gives you information for installation and usage of Mupel

-------------
### License of Muple
- [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](LICENSE)

-------------
### License of kodi
- [GNU GENERAL PUBLIC LICENSE Version 2, June 1991](https://github.com/xbmc/xbmc/raw/master/LICENSE.GPL)

-------------
### License of CEF
- Copyright (c) 2008-2014 Marshall A. Greenblatt. Portions Copyright (c)
- 2006-2009 Google Inc. All rights reserved.
- [New BSD License](https://bitbucket.org/chromiumembedded/cef/raw/master/LICENSE.txt)
