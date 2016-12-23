# Fluid Engine Dev - Jet

[![License](http://img.shields.io/:license-mit-blue.svg)](LICENSE.md) [![Build Status](https://travis-ci.org/doyubkim/fluid-engine-dev.svg?branch=master)](https://travis-ci.org/doyubkim/fluid-engine-dev) [![Build status](https://ci.appveyor.com/api/projects/status/kulihlhy43vbwou6/branch/master?svg=true)](https://ci.appveyor.com/project/doyubkim/fluid-engine-dev/branch/master)

Jet framework is a fluid simulation engine SDK for computer graphics applications that was created by Doyub Kim as part of the book, ["Fluid Engine Development"](https://www.crcpress.com/Fluid-Engine-Development/Kim/p/book/9781498719926). The code is built on C++11 and can be compiled with commonly available compilers such as g++, clang, and Visual Studio. Currently tested platforms are macOS (10.10 or later), Ubuntu (14.04 or later), and Windows (Visual Studio 2015).

### Key Features
* SPH and PCISPH fluid simulators
* Stable fluids-based smoke simulator
* Level set-based liquid simulator
* PIC and FLIP fluid simulators
* Upwind, ENO and FMM level set solvers
* Converters between signed distance function and triangular mesh

Every simulator has both 2-D and 3-D implementations.

## How to Build

To learn how to build, test, and install the SDK, please check out [INSTALL.md](https://github.com/doyubkim/fluid-engine-dev/blob/master/INSTALL.md).

## Examples

Here are some of the example simulations generated using Jet framework. Corresponding example codes can be found under src/examples. All images are rendered using [Mitsuba renderer](https://www.mitsuba-renderer.org/).

![Examples](https://github.com/doyubkim/fluid-engine-dev/raw/master/doc/img/examples.png "Examples")

## License

Jet is under the MIT license. For more information, check out [LICENSE.md](https://github.com/doyubkim/fluid-engine-dev/blob/master/LICENSE.md). Jet also utilizes other open source codes. Checkout [3RD_PARTY.md](https://github.com/doyubkim/fluid-engine-dev/blob/master/3RD_PARTY.md) for more details.