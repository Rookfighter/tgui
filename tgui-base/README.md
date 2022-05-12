# tgui-base build2 package

[![cppget](https://img.shields.io/website/https/cppget.org/tgui-base.svg?down_message=offline&label=cppget.org&up_color=blue&up_message=online)](https://cppget.org/tgui)

This project builds and defines the build2 package for the `tgui-base` package.
This package does not contain any backends for working with TGUI.
It is not meant to be used directly but serves as base for the packages with actual backends like SFML or SDL.

## Usage

Add `tgui-base` to your build2 `manifest` file.

```
depends: tgui-base ^0.9.3
```