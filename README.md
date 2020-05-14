Plex Media Player - Debian Package for x86
===========================================

## Introduction

This repository hopes to automate building Debian .deb packages for the Plex Media Player application, primarily (but not exclusively) targetting OpenFrame devices.

However, I've never done this before, so at the moment it does nothing.

## Building

There are a shed load of build dependencies and I'm still compiling the list.


## Source

Packages are build from official Plex Media Player source code without any modifications. Plex source code repository is available on GitHub.

https://github.com/plexinc/plex-media-player

## Binary Dependencies

These are the dependencies currently fed manually into [checkinstall](https://github.com/giuliomoro/checkinstall).

```
libmpv1,libqt5xml5,libqt5webengine5,libqt5widgets5,libqt5x11extras5,libqt5quick5,libqt5quickcontrols2-5,qml-module-qtwebchannel,qml-module-qtwebengine,qml-module-qtquick-controls2,xserver-xorg,xserver-xorg-legacy,x11-utils,xinit
```