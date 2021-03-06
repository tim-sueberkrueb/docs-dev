# Liri Developers Documentation

## Introduction

Liri uses [Qt](https://www.qt.io), a cross-platform framework, to build apps and libraries.

The IDE of choice is [QtCreator](https://www.qt.io/ide/) a cross-platform IDE dedicated to development with Qt.

All projects use the Qbs build system, a new build system that is much easier to use compared to qmake or CMake.
If you want to learn more, please read the [Qbs manual](http://doc.qt.io/qbs/index.html),
especially the [setup guide](http://doc.qt.io/qbs/configuring.html) and how to install artifacts
from the [installation guide](http://doc.qt.io/qbs/installing-files.html).

Source code is managed with [git](https://git-scm.com/) and we use the
[git flow](http://nvie.com/posts/a-successful-git-branching-model/) workflow.

This means, in a nutshell, that the latest released code is in the `master` branch while development
happens in the `develop` branch.

## Getting Started

Liri requires a recent version of Qt therefore we recommend to develop on Arch Linux,
because it is a great distro for developers and the software is always up to date.

Some distributions like Ubuntu have very old Qt copies. If you cannot switch to Arch Linux,
please consider installing the binaries provided by The Qt Company.

Download the [online installer](https://www1.qt.io/download-open-source/) and install both
Qt and QtCreator. However keep in mind that the binaries provided by The Qt Company do not
have QtWayland, this means that you will not be able to develop Liri Shell.