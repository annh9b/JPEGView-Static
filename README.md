# JPEGView Second Life - Image Viewer and Editor

Second life for famous [JPEGView from SourceForge.net - last updated 2018-03-10, currently abandoned](https://sourceforge.net/projects/jpegview/) - fast and tiny viewer/editor for JPEG, BMP, PNG, WEBP, TGA, GIF and TIFF images with a minimalist GUI and base image processing.

This fork incorporates changes not only from original [JPEGView from SourceForge.net](https://sourceforge.net/projects/jpegview/),
but also from [JPEGView at GitHub user sylikc](https://github.com/sylikc/jpegview).

![JPEGView Second Life icon](favicon_large.png?raw=true)

> Updated Nov 02 2022. JPEGView Second Life version 1.2.0.0 has been released. Portable zip-archive has been added. Windows installer made with [Inno Setup](https://jrsoftware.org/isinfo.php). Collaboration with [Second Life Metaverse](https://en.wikipedia.org/wiki/Second_Life) started, details below.

**All the binaries (Windows installer, portable zip-archive) can be downloaded from [Official Site](https://www.open-source.tech/JPEGView-Image-Viewer-and-Editor/).**

## Collaboration with [Second Life Metaverse](https://en.wikipedia.org/wiki/Second_Life)

JPEGView Second Life appears to be extremely useful in converting [WebP](https://en.wikipedia.org/wiki/WebP) files to jpg images
since JPEGView Second Life incorporates a [Google's WebP library](https://chromium.googlesource.com/webm/libwebp).
By default, JPEGView Second Life saves high quality yet relatively small jpg images, using [Turbo JPEG library](https://libjpeg-turbo.org).

JPEGView Second Life was [used](https://secondlife.com/destination/metaverse-city) to convert Second Life Metaverse
[avatars](https://www.pcgamer.com/second-life-metaverse-interview/) and [screenshots](https://mitsloan.mit.edu/ideas-made-to-matter/what-second-life-and-roblox-can-teach-us-about-metaverse)
into jpg file format. Below are few examples of how easily that can be achieved.

* JPEGView Second Life: Metaverse City is a welcoming roleplay community aimed towards newcomers and veterans alike

![JPEGView Second Life: Metaverse City is a welcoming roleplay community aimed towards newcomers and veterans alike](screenshots/JpegView-SL-1.jpg?raw=true)

* JPEGView Second Life: Philip Rosedale is one of the few people in the world who can genuinely be called a metaverse pioneer

![JPEGView Second Life: Philip Rosedale is one of the few people in the world who can genuinely be called a metaverse pioneer](screenshots/JpegView-SL-2.jpg?raw=true)

* JPEGView Second Life: As companies explore what a robust metaverse means for them, executives from Second Life and Roblox offer guidance

![JPEGView Second Life: As companies explore what a robust metaverse means for them, executives from Second Life and Roblox offer guidance](screenshots/JpegView-SL-3.jpg?raw=true)

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

## Help

* [English](https://www.open-source.tech/JPEGView-Image-Viewer-and-Editor/readme.html)
* [Ukrainian](https://www.open-source.tech/JPEGView-Image-Viewer-and-Editor/readme-ua.html)
* [Russian](https://www.open-source.tech/JPEGView-Image-Viewer-and-Editor/readme-ru.html)
