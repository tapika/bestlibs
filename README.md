# Overview

On my daily work I'm constatly hitting accross one or another library or technique - all of libraries have their own advantages,
weaknesses and side effects. I've decided to collect here some of libraries.

If you know some good library, article, youtube video, feel free to send me mail to tapika-at-yahoo-dot-com with your collection of links, I'll try to analyze and add them into my own list. I will not necessarily add your links without deeper analysis of library/article.

## Programming Languages

  * [C++](https://github.com/tapika/bestlibs/tree/main/cpp)

## Game Engines

*Libraries dealing with game development*

* Godot Engine (C++)
  * [Godot git](https://github.com/godotengine/godot), [Main web page](https://godotengine.org/) [MIT]
  * Articles:
    * [Is Making Advanced GUI Applications with Godot the Future?](https://medium.com/swlh/what-makes-godot-engine-great-for-advance-gui-applications-b1cfb941df3b)

## File formats

*Various file formats - serialization / deserialization*

[The state of config file formats: XML vs. YAML vs. JSON vs. HCL](https://octopus.com/blog/state-of-config-file-formats)

### [Json](https://en.wikipedia.org/wiki/JSON)

Json originated from JavaScript Object Notation, which came originally from Javascript. Json is standartized to some level, json comments are not necessarily taken into json standard - it depends on json parsing library itself. If we need to interoperate between programming languages (for example c++ and javascript) - then such interoperability file format might be handy. 3rd-party remote procedure call libraries, like Google protobuf, might be capable or direct serialization to json without separate json library.

* [We released simdjson 0.3: the fastest JSON parser in the world is even better](https://lemire.me/blog/2020/03/31/we-released-simdjson-0-3-the-fastest-json-parser-in-the-world-is-even-better/)
  * [simdjson, C++, git](https://github.com/simdjson/simdjson) [Apache]

## Logging

* [In Russian: C++, Сравнение библиотек логирования, 2016](https://habr.com/ru/post/313686/)
* [C#, Benchmarking 5 popular .NET logging libraries, 2016](https://www.loggly.com/blog/benchmarking-5-popular-net-logging-libraries/)

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
  * [ninja, C++](https://github.com/ninja-build/ninja) [Apache] Ninja focuses on building, mainly C++ components. Already built-in in Visual studio and moreover make project generation systems (e.g. cmake) produce ninja file format as output file. Much faster compared to msbuild.

# Various link collections:

* [Awesome C++ - various C++ library link collection](https://github.com/fffaraz/awesome-cpp) (This git was initially inspired by Awesome C++ link collection)

