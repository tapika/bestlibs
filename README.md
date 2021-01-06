# Overview

On my daily work I'm constatly hitting accross one or another library or technique - all of libraries have their own advantages,
weaknesses and side effects. I've decided to collect here some of libraries.

## Programming Languages

  * [C++](https://github.com/tapika/bestlibs/tree/main/cpp)

## Game Engines

*Libraries dealing with game development*

* Godot Engine (C++)
  * [Godot git](https://github.com/godotengine/godot), [Main web page](https://godotengine.org/) [MIT]
  * Articles:
    * [Is Making Advanced GUI Applications with Godot the Future?](https://medium.com/swlh/what-makes-godot-engine-great-for-advance-gui-applications-b1cfb941df3b)

## Logging

* (In Russian: C++, Сравнение библиотек логирования, 2016)[https://habr.com/ru/post/313686/]
* (C#, Benchmarking 5 popular .NET logging libraries, 2016)[https://www.loggly.com/blog/benchmarking-5-popular-net-logging-libraries/]

## Testing

*Libraries dealing with testing*

  1. [xunit, C#](https://xunit.net) [MIT] - Targetting for C# unit testing. Unlike built-in Visual studio platform support `[Theory]` kind of attribute, which
  allows to specify custom input arguments to each test. Test host application is executed in same process, unlike Visual studio platform.


## Installation

*Libraries dealing with package building and installation*

  1. [Chocolatey, C#](https://github.com/chocolatey/choco) [MIT] - Based on nuget client/server architecture chocolatey deals with software installation, upgrade, uninstallation
  2. [Microsoft MSIX packaging, C++](https://github.com/microsoft/msix-packaging) [MIT] - Package management primarily targetted for Windows.

## 3rd Party Library Building

  * [Microsoft vcpkg, C++/cmake](https://github.com/microsoft/vcpkg) [MIT] tool for building various 3rd party packages for Windows. Even thus tool focuses on building 3rd party libraries, patches for 3rd-party libraries are located within vcpkg repository. vcpkg is not targetting to become industry standard installation system, which leaves it on build tool level, like msbuild or similar.

# Various link collections:

* [Awesome C++ - various C++ library link collection](https://github.com/fffaraz/awesome-cpp) (This git was initially inspired by Awesome C++ link collection)

