# AntiDupl.NET

![AntiDupl.net screenshot](https://ermig1979.github.io/AntiDupl/data/help/english/files/MainForm.png)

Modern users have many image in various formats. As the number of images grows, so is the odds of
having undesired duplicates. However, if the collection is large enough, manual deduplication is
tedious and unproductive. AntiDupl.NET will help you automate this process. It can find and display
duplicate images in the following formats: JPEG, GIF, TIFF, BMP, PNG, EMF, WMF, WEBP, EXIF, ICON,
JP2, PSD, DDS, HEIF, HEIC, TGA, AVIF and JXL. The comparison is based on the contents of the files,
so the program can find not only almost identical, but similar images. In addition, the program can
find images with some types of defects.

[AntiDupl.NET](http://ermig1979.github.io/AntiDupl) is free and open-source. It is easy to use, has
high speed and accuracy, and supports Russian and English interface.

## Building AntiDupl.NET

1. Download Visual Studio 2022. The Community edition is enough:

    <https://visualstudio.microsoft.com/vs/community/>

2. Install the following Visual Studio workloads and components:

    - ".NET Desktop development"
      - "Development tools for .NET"
    - "Desktop development with C++"
      - "MSVC v143 - VS 2022 C++ x64/x86 build tools (latest)"
      - "C++ CMake tools for Windows"
      - "vcpkg package manager"

3. Open the Visual Studio solution file at `src\AntiDupl.sln`

4. Build the solution

Visual Studio will download any required packages before building via `vcpkg`.

## AntiDuplX, the command-line tool

[AntiDuplX](https://github.com/ermig1979/AntiDuplX) is a command-line tool for finding similar and damaged images.
This is standalon project which uses similar algorithm of image comparison. It works for Linux and Windows.
