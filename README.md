namp-lite - ncurses audio media player (lite version)
=====================================================

| **Linux** |
|-----------|
| [![Linux](https://github.com/d99kris/namp-lite/workflows/Linux/badge.svg)](https://github.com/d99kris/namp-lite/actions?query=workflow%3ALinux) |

namp-lite is a console-based MP3 player for Linux. It is the lite version of
[namp](https://github.com/d99kris/namp) with no dependency on Qt.

![namp screenshot](/doc/namp-screenshot.png)

Features
========
- Supported file formats: MPEG 1.0/2.0/2.5 stream (layers 1, 2 and 3).
- Support for last.fm scrobbling
- Support for enqueueing tracks
- Infinite track (back) history
- Mouse support

Supported Platforms
===================
namp should work on most Linux systems where its dependencies are met;
libmpg123, libao, libasound, libcurl, libcrypto, libtag, libncursesw, libglib2 and help2man.

Current version has been tested on:
- Ubuntu 20.04 LTS

Dependencies
============

Ubuntu / Debian
---------------

    sudo apt install build-essential libtool autoconf automake libglib2.0-dev libncursesw5-dev libmpg123-dev libao-dev libasound2-dev libtagc0-dev libcurl4-openssl-dev libssl-dev help2man

openSUSE
--------
Note: Some packages below are not available in standard repositories, but can be installed from for example packman-essentials.

    sudo zypper install make gcc glib2-devel ncurses-devel libmpg123-devel libao-devel alsa-devel libtag-devel libcurl-devel libopenssl-devel help2man

Installation
============
Configure and build:

    autoreconf -f -i && ./configure && make -s

Optionally install:

    sudo make install

Usage
=====
Refer to man-page or 'namp --help'.

License
=======
namp is distributed under GPLv2 license. See LICENSE file.

Keywords
========
console, linux, mp3 player, music player, ncurses, terminal.

