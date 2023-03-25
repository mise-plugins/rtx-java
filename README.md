# rtx-java

[![Build status](https://github.com/rtx-plugins/rtx-java/workflows/rtx-java%20Tests/badge.svg?branch=main)](https://github.com/rtx-plugins/rtx-java/actions?query=workflow%3A%rtx-java+Tests%22+branch%main) [![Join the chat at https://gitter.im/asdf-java/community](https://badges.gitter.im/asdf-java/community.svg)](https://gitter.im/asdf-java/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[Java](https://www.java.com/en/) plugin for the [rtx](https://github.com/jdxcode/rtx) version manager.

## Requirements
- [bash v5.0](https://www.gnu.org/software/bash/)
- [curl](https://curl.haxx.se/)
- [sha256sum](https://www.gnu.org/software/coreutils/) (only on Linux)
- [unzip](http://infozip.sourceforge.net/UnZip.html)

## Install

```
rtx plugin add java
```

## Use

Check [rtx](https://rtx.pub/) for instructions on how to install & manage versions of Java.

## Install

List candidate JDKs:

`rtx ls-remote java`

Install a candidate listed from the previous command like this:

`rtx install java@adopt-openjdk-12`

Select an installed candidate for use like this:

`rtx global java@adopt-openjdk-12`
