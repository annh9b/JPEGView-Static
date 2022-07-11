# JPEGView-Image-Viewer-and-Editor

> Updated Jul 11 2022. JPEGView Second Life version 1.2.0.0 has been released ([download](https://filedn.com/llBp1EbMQML0Hdv9A9SVo6b/Setup-JPEGViewSecondLife-v1.2.0.0-x64.exe)). Windows installer made with [Inno Setup](https://jrsoftware.org/isinfo.php).

Second life for famous [JPEGView from SourceForge.net - last updated 2018-03-10, currently abandoned](https://sourceforge.net/projects/jpegview/) - fast and tiny viewer/editor for JPEG, BMP, PNG, WEBP, TGA, GIF and TIFF images with a minimalist GUI and base image processing.

This fork incorporates changes not only from original [JPEGView from SourceForge.net](https://sourceforge.net/projects/jpegview/),
but also from [JPEGView at GitHub user sylikc](https://github.com/sylikc/jpegview).

Binaries can be downloaded from [Official Site](https://www.open-source.tech/JPEGView-Image-Viewer-and-Editor/).

## Features

* Small and fast, uses SSE2 and up to 4 CPU cores.
* High quality resampling filter, preserving sharpness of images.
* Basic image processing tools can be applied realtime during viewing.
* Movie mode to play folder of JPEGs as movie.

## Official Site

Brand new Windows installer can be downloaded there.

[www.open-source.tech/JPEGView-Image-Viewer-and-Editor/](https://www.open-source.tech/JPEGView-Image-Viewer-and-Editor/)

![www.open-source.tech/JPEGView-Image-Viewer-and-Editor/ screenshot](open-source-tech.jpg?raw=true)

## What's new (briefly)

* Windows installer made with [Inno Setup](https://jrsoftware.org/isinfo.php)
* Removed obsolete Visual Studio solutions 2013, 2017, etc. VS2019 is the only supported now.
* Included WTL library into repository. No external dependencies remained. Just git-clone and build.
* Updated to much faster Turbo JPEG library version 2.1.0 (4/23/2021).
* Updated to Google's WebP library version 1.2.0 HEAD at commit 05b72d4 (4/28/2021).
