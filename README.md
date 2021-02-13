# Overview

On my daily work I'm constatly hitting accross one or another library or technique - all of libraries have their own advantages,
weaknesses and side effects. I've decided to collect here some of libraries.

If you know some good library, article, youtube video, feel free to send me mail to tapika-at-yahoo-dot-com with your collection of links, I'll try to analyze and add them into my own list. I will not necessarily add your links without deeper analysis of library/article.

## Languages

  * [Programming Language: C++](https://github.com/tapika/bestlibs/tree/main/cpp)
  * [Natural languages](https://github.com/tapika/bestlibs/tree/main/naturallanguage)

## Comparison web sites

*Various web sites which compare libraries, tools, frameworks with each other*

  * [AlternativeTo](https://alternativeto.net/) Web site, which can compare applications, tools, technologies to each other.
  * [Libraries.io](https://libraries.io/) Web site, which can compare different libraries to each other.

## Game Engines

*Libraries dealing with game development*

[What are the best game engines?](https://www.slant.co/topics/991/~best-game-engines) Brief comparison of game engines.

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
* [.Net Logging Performance Comparison, .NET logging libraries, 2019](https://medium.com/@imanushin/net-logging-performance-comparison-20c83aa84333)
* [C#, Benchmarking 5 popular .NET logging libraries, 2016](https://www.loggly.com/blog/benchmarking-5-popular-net-logging-libraries/)

Most obvious choice for C# logging is [NLog](https://nlog-project.org/), for C++ - `[spdlog](https://github.com/gabime/spdlog)`.

## Testing

*Libraries dealing with testing*

  1. [xunit, C#](https://xunit.net) [MIT] - Targetting for C# unit testing. Unlike built-in Visual studio platform support `[Theory]` kind of attribute, which
  allows to specify custom input arguments to each test. Test host application is executed in same process, unlike Visual studio platform.


## Installation

*Libraries dealing with package building and installation*

  1. [Chocolatey, C#](https://github.com/chocolatey/choco) [MIT] - Based on nuget client/server architecture chocolatey deals with software installation, upgrade, uninstallation
  2. [Microsoft MSIX packaging, C++](https://github.com/microsoft/msix-packaging) [MIT] - Package management primarily targetted for Windows.

## 3rd Party Library Building

*Libraries dealing with 3rd party libraries building or generally building, partially also covered in C++-language itself, as C++ is not yet "standalone" language itself*

* [Microsoft vcpkg, C++/cmake](https://github.com/microsoft/vcpkg) [MIT] tool for building various 3rd party packages for Windows. Even thus tool focuses on building 3rd party libraries, patches for 3rd-party libraries are located within vcpkg repository. vcpkg is not targetting to become industry standard installation system, which leaves it on build tool level, like msbuild or similar.
* [ninja, C++](https://github.com/ninja-build/ninja) [Apache] Ninja focuses on building, mainly C++ components. Already built-in in Visual studio and moreover make project generation systems (e.g. cmake) produce ninja file format as output file. Much faster compared to msbuild. Does not needs to be used directly by developers, normally build system (e.g. make, cmake, visual studio based uses ninja for their own purpose)

# Various link collections:

* [Awesome C++ - various C++ library link collection](https://github.com/fffaraz/awesome-cpp) (This git was initially inspired by Awesome C++ link collection)

