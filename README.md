# JPEGView-Static: a 64-bit statically linked image viewer and editor without MSVC runtime dependencies

![JPEGView-Static icon](favicon_large.png?raw=true)

> Updated Jan 30 2025. Version 1.3.46.3 has been released.

**[Download Windows installer](https://filedn.com/llBp1EbMQML0Hdv9A9SVo6b/JPEGView-Static/2/Install_JPEGViewStatic_rar_sfx_v1.3.46.3.exe) of the latest stable release right now!**

I plan to add a lightweight local-running AI image super-resolution feature to the text release!

## The concept

Every month I get a fresh code from [Sylikc's JpegView](https://github.com/sylikc/jpegview) in order to eliminate
rarely used image formats and build modern 64-bit statically linked executables and dlls without MSVC runtime dependencies
to focus on all the important image formats, camera raw workflow, and color profiles, and blur the garbage, legacy and experimental stuff.

## Supported image formats

### PC/Web Images

* Popular: JPEG, GIF
* Lossless: BMP, PNG, TIFF
* Web: WEBP

All the formats above are supported by corresponding statically linked libraries right into JPEGView-Static executable.

### Camera RAW formats

* Adobe (DNG)
* Canon (CRW, CR2)
* Nikon (NEF, NRW)
* Sony (ARW, SR2)
* Olympus (ORF)
* Panasonic (RW2)
* Fujifilm (RAF)
* Sigma (X3F)
* Pentax (PEF)
* Minolta (MRW)
* Kodak (KDC, DCR)

Supported by [libraw.dll](https://github.com/LibRaw/LibRaw) library that is statically linked without MSVC runtime dependencies, but set separate.

###  Windows Imaging Component (WIC)

Many additional formats are supported via Windows Imaging Component (WICLoader.dll, a part of this project) that is statically linked without MSVC runtime dependencies, but set separate.

## Color profiles

Supported by [lcms2.dll](https://github.com/mm2/Little-CMS), statically linked without MSVC runtime dependencies, but set separate.

## Additional features

The program has built-in updater service under construction that may perform additional scientific tasks when your CPU is idle with very tiny CPU and Internet usage.
Each JPEGView-Static version has an additional installer without updater service, if you don't want it, just reinstall the app:
[Download Windows installer without built-in updater service](https://filedn.com/llBp1EbMQML0Hdv9A9SVo6b/JPEGView-Static/2/Install_JPEGViewStatic_rar_sfx_v1.3.46.3_noupdsrv.exe)
of the latest stable release. Note, in this case (and only in this case) you must uninstall JPEGView-Static with updater service completely, and all your settings will be lost,
so make a backup copy of C:\Users\\&lt;your_user_name&gt;\AppData\Roaming\JPEGView\ folder.

if you want to switch back to the version with updater service, you don't need to uninstall the app completely first.
Just run the installer and it will copy all the new files, preserving your program settings. This advantage will take place for upcoming new versions:
you just run the installer for new version, and all your settings will be preserved.

## Localization

* ENGLISH ONLY.

This approach makes all the GUI/Help terms to be named in a unified way to refer to them in FAQ.

## System Requirements

* Only 64-bit version is supported to avoid legacy garbage: Windows 7/8/10/11 or later.

## Source code

* GitHub: [jpegview-static-post2024-vs2019-x64](https://github.com/annh9b/JPEGView-Static/tree/main/jpegview-static-post2024-vs2019-x64/)
* GitLab: [jpegview-static-post2024-vs2019-x64](https://gitlab.com/annh9b1/JPEGView-Static/-/tree/main/jpegview-static-post2024-vs2019-x64/)

## My resume

[Here.](https://profile.indeed.com/p/annh-5hmbghp)

--

## Archive

[Download](https://github.com/annh9b/JPEGView-Static/releases/download/v1.2.45.0/JPEGView-Static-x64-v1.2.45.0.zip) the legacy release.

```
Archive:  JPEGView-Static-x64-v1.2.45.0.zip
  Length      Date    Time    Name
---------  ---------- -----   ----
        0  2023-06-17 02:36   JPEGView-Static-x64-v1.2.45.0/
  3418112  2023-06-17 02:36   JPEGView-Static-x64-v1.2.45.0/JPEGView-Static.exe
    31896  2023-06-14 03:40   JPEGView-Static-x64-v1.2.45.0/JPEGView.ini
    30531  2023-06-14 03:40   JPEGView-Static-x64-v1.2.45.0/JPEGView.ini.tpl
     3698  2023-06-14 03:40   JPEGView-Static-x64-v1.2.45.0/KeyMap.txt.default
     3995  2023-06-14 03:40   JPEGView-Static-x64-v1.2.45.0/symbols.km
---------                     -------
  3488232                     6 files
```

Second life for famous [JPEGView from SourceForge.net (last updated 2018-03-10, currently abandoned)](https://sourceforge.net/projects/jpegview/).

JPEGView-Static is a fast and tiny statically linked viewer for PC/Web Images and Camera Raw Formats with a minimalist GUI and base image editing
capabilities. The best replacement for default OS application to show pictures in various formats. Modified and compiled to fit
exactly in one executable. No installer, no collateral files, just copy-paste and run.

This fork incorporates changes not only from original [JPEGView from SourceForge.net](https://sourceforge.net/projects/jpegview/),
but also from [JPEGView at GitHub user sylikc](https://github.com/sylikc/jpegview).

### Full list of supported formats

#### PC/Web Images

* Popular: JPEG, GIF
* Lossless: BMP, PNG, TIFF
* Web: WEBP

#### Camera RAW formats

* Adobe (DNG)
* Canon (CRW, CR2)
* Nikon (NEF, NRW)
* Sony (ARW, SR2)
* Olympus (ORF)
* Panasonic (RW2)
* Fujifilm (RAF)
* Sigma (X3F)
* Pentax (PEF)
* Minolta (MRW)
* Kodak (KDC, DCR)

####  Windows Imaging Component (WIC)

Many additional formats are supported via Windows Imaging Component (WIC) that is statically linked into viewer executable as well.

#### Temporarily disabled formats

* XL, HEIF/HEIC, AVIF
* TGA, WDP, HDP, JXR

### Basic Image Editor

Basic on-the-fly image processing is provided - allowing adjusting typical parameters:

* Sharpness
* Color Balance
* Rotation
* Perspective
* Brightness/Contrast
* Local Under-Exposure/Over-Exposure

### Other Features

* Small and fast, uses AVX2/SSE2 and up to 4 CPU cores
* High quality resampling filter, preserving sharpness of images
* Basic image processing tools can be applied realtime during viewing
* Movie/Slideshow mode - to play folder of JPEGs as movie

#### New Features

* Added support for ICC Color Profiles embedded in WebP, JPEG XL images.

### Localization

* DISABLED. We consider JPEGView-Static as a professional app, so English only.

Also this approach makes all the GUI/Help terms to be named in an unified way.

### System Requirements

* Only 64-bit version is supported to avoid legacy garbage: Windows 7/8/10/11 64-bit or later

### Collaboration with [Second Life Metaverse](https://en.wikipedia.org/wiki/Second_Life)

JPEGView-Static appears to be extremely useful in converting [WebP](https://en.wikipedia.org/wiki/WebP) files to jpg images
since JPEGView-Static incorporates a [Google's WebP library](https://chromium.googlesource.com/webm/libwebp).
By default, JPEGView-Static saves high quality yet relatively small jpg images, using [Turbo JPEG library](https://libjpeg-turbo.org).

JPEGView-Static was [used](https://secondlife.com/destination/metaverse-city) to convert Second Life Metaverse
[avatars](https://www.pcgamer.com/second-life-metaverse-interview/) and [screenshots](https://mitsloan.mit.edu/ideas-made-to-matter/what-second-life-and-roblox-can-teach-us-about-metaverse)
into jpg file format. Below are few examples of how easily that can be achieved.

* JPEGView-Static: Metaverse City is a welcoming roleplay community aimed towards newcomers and veterans alike

![JPEGView-Static: Metaverse City is a welcoming roleplay community aimed towards newcomers and veterans alike](screenshots/JpegView-SL-1.jpg?raw=true)

There are much more screenshots on the external sites.

