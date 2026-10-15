# OPENSCAD

> Anticloud offline package — upstream: openscad/openscad @ `master`.

## What This Project Does

OpenSCAD - The Programmers Solid 3D CAD Modeller  

**Topics:** 3d, 3d-graphics, 3d-models, 3d-printing, c-plus-plus, c-plus-plus-17, cad, dxf-files, linux, macos, opengl, openscad, qt5, qt6, windows

## Upstream README

[![GitHub (master)](https://img.shields.io/github/checks-status/openscad/openscad/master.svg?logo=github&label=build&logoColor=black&colorA=f9d72c&style=plastic)](https://github.com/openscad/openscad/actions)
[![CircleCI (master)](https://img.shields.io/circleci/project/github/openscad/openscad/master.svg?logo=circleci&logoColor=black&colorA=f9d72c&style=plastic)](https://circleci.com/gh/openscad/openscad/tree/master)
[![Coverity Scan](https://img.shields.io/coverity/scan/2510.svg?colorA=f9d72c&logoColor=black&style=plastic)](https://scan.coverity.com/projects/2510)

[![Visit our IRC channel](https://kiwiirc.com/buttons/irc.libera.chat/openscad.png)](https://kiwiirc.com/client/irc.libera.chat/#openscad)

# What is OpenSCAD?
<p><a href="https://opencollective.com/openscad/donate"><img align="right" src="https://opencollective.com/openscad/donate/button@2x.png?color=white" width="200"/></a>

OpenSCAD is a software for creating solid 3D CAD objects. It is free software and
available for Linux/UNIX, MS Windows and macOS.</p>

Unlike most free software for creating 3D models (such as the famous
application Blender), OpenSCAD focuses on the CAD aspects rather than the
artistic aspects of 3D modeling. Thus this might be the application you are
looking for when you are planning to create 3D models of machine parts but
probably not the tool for creating computer-animated movies.

OpenSCAD is not an interactive modeler. Instead it is more like a
3D-compiler that reads a script file that describes the object and renders
the 3D model from this script file (see examples below). This gives you, the
designer, complete control over the modeling process and enables you to easily
change any step in the modeling process or make designs that are defined by
configurable parameters.

OpenSCAD provides two main modeling techniques: First there is constructive
solid geometry (aka CSG) and second there is extrusion of 2D outlines. As the data
exchange format for these 2D outlines Autocad DXF files are used. In
addition to 2D paths for extrusion it is also possible to read design parameters
from DXF files. Besides DXF files OpenSCAD can read and create 3D models in the
STL and OFF file formats.

# Contents

- [Getting Started](#getting-started)
- [Documentation](#documentation)
    - [Building OpenSCAD](#building-openscad)
        - [Prerequisites](#prerequisites)
        - [Getting the source code](#getting-the-source-code)
        - [Building for macOS](#building-for-macos)
        - [Building for Linux/BSD](#building-for-linuxbsd)
        - [Building for Linux/BSD on systems with older or missing dependencies](#building-for-linuxbsd-on-systems-with-older-or-missing-dependencies)
        - [Building for Windows](#building-for-windows)
        - [Compilation](#compilation)

# Getting started

You can download the latest binaries of OpenSCAD at
<https://www.openscad.org/downloads.html>. Install binaries as you would any other
software.

When you open OpenSCAD, you'll see 

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
