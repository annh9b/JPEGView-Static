# JPEGView-Static - Image Viewer and Editor

Second life for famous [JPEGView from SourceForge.net - last updated 2018-03-10, currently abandoned](https://sourceforge.net/projects/jpegview/) - fast and tiny viewer/editor for JPEG, BMP, PNG, WEBP, TGA, GIF and TIFF images with a minimalist GUI and base image processing.

This fork incorporates changes not only from original [JPEGView from SourceForge.net](https://sourceforge.net/projects/jpegview/),
but also from [JPEGView at GitHub user sylikc](https://github.com/sylikc/jpegview).

![JPEGView-Static icon](favicon_large.png?raw=true)

> Updated Jun 16 2023. JPEGView-Static is the new project name and purpose: all the stuff needed in exactly one statically linked executable.

## Collaboration with [Second Life Metaverse](https://en.wikipedia.org/wiki/Second_Life)

JPEGView-Static appears to be extremely useful in converting [WebP](https://en.wikipedia.org/wiki/WebP) files to jpg images
since JPEGView-Static incorporates a [Google's WebP library](https://chromium.googlesource.com/webm/libwebp).
By default, JPEGView-Static saves high quality yet relatively small jpg images, using [Turbo JPEG library](https://libjpeg-turbo.org).

JPEGView-Static was [used](https://secondlife.com/destination/metaverse-city) to convert Second Life Metaverse
[avatars](https://www.pcgamer.com/second-life-metaverse-interview/) and [screenshots](https://mitsloan.mit.edu/ideas-made-to-matter/what-second-life-and-roblox-can-teach-us-about-metaverse)
into jpg file format. Below are few examples of how easily that can be achieved.

* JPEGView-Static: Metaverse City is a welcoming roleplay community aimed towards newcomers and veterans alike

![JPEGView-Static: Metaverse City is a welcoming roleplay community aimed towards newcomers and veterans alike](screenshots/JpegView-SL-1.jpg?raw=true)

* JPEGView-Static: Philip Rosedale is one of the few people in the world who can genuinely be called a metaverse pioneer

![JPEGView-Static: Philip Rosedale is one of the few people in the world who can genuinely be called a metaverse pioneer](screenshots/JpegView-SL-2.jpg?raw=true)

* JPEGView-Static: As companies explore what a robust metaverse means for them, executives from Second Life and Roblox offer guidance

![JPEGView-Static: As companies explore what a robust metaverse means for them, executives from Second Life and Roblox offer guidance](screenshots/JpegView-SL-3.jpg?raw=true)

## Features

* Small and fast, uses SSE2 and up to 4 CPU cores.
* High quality resampling filter, preserving sharpness of images.
* Basic image processing tools can be applied realtime during viewing.
* Movie mode to play folder of JPEGs as movie.
