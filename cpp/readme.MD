# C++ Language

Here are listed various C++ improvements ideas / concepts / C++ standartization techiques.

[C++ Standards Committee](http://www.open-std.org/jtc1/sc22/wg21/) C++ improvements list - aiming for C++ improvements.

## Project generation tools

*Libraries which try to make C++ development portable accross different OS's, they try to generate project files suitable for different build systems, OS's, IDE's*

1. [cmake web page](https://cmake.org/). Custom cmake dialect, which was originally made to help C++ to simplify project generation - but nowadays is more or less 
a standard because it's built-in into Visual studio and Qt. cmake dialect is bit difficult to learn and maintain.

2. [SCons project generation tool (Used within Godot game engine)](https://docs.godotengine.org/en/stable/development/compiling/introduction_to_the_buildsystem.html) Another project generation tool, written in Python. Advances over other project generation tools are mentioned on Godot web page.

## Make C++ Scriptable

*There are various attempts to make C++ scriptable*

1. [cling interactive C++ scripting](https://github.com/root-project/cling) [MIT].

  * Articles/Blogs:
    * [Interactive C++ with Cling](https://blog.llvm.org/posts/2020-11-30-interactive-cpp-with-cling/)

Based on older LLVM/clang compiler (5.0) cling is command line tool for compiling and executing C++ directly.

2. [Clang with just-in-time (JIT) compilation extensions](https://github.com/hfinkel/llvm-project-cxxjit) Clang with JIT extensions.

  * Articles:
    * [Just-in-Time Compilation: The Next Big Thing? - Ben Deane & Kris Jusiak - CppCon 2020](https://www.youtube.com/watch?v=I3ov8HcdVKw)
    * [P1609R1 - C++ Should Support Just-in-Time Compilation](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p1609r1.html) Proposal to make this as a C++ standard.

Experimental proposal of enabling JIT on C++ compiler - targetted for linux and clang compiler.

* [C++ chai script](http://chaiscript.com/) [BSD] - small simplified C++ parser, which is not directly C++, but some sort of it's modification (Chai script), which is capable of evaluating and executing C++-like script. Not fully C++ compliant, but also can live in portable / separate chai script box.

* [Runtime Compiled C++](https://github.com/RuntimeCompiledCPlusPlus/RuntimeCompiledCPlusPlus) Focuses on compiling C++ in a script manner. Does not have good project scripting language (cmake, python, etc...), but it's own C++ defines. Combines configuration and build tool in one.

