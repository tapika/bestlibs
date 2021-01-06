# C++ Language

Here are listed various C++ improvements ideas / concepts / C++ standartization techiques.

## Project generation tools

*Libraries which try to make C++ development portable accross different OS's, they try to generate project files suitable for different build systems, OS's, IDE's*

1. [cmake web page](https://cmake.org/). Custom cmake dialect, which was originally made to help C++ to simplify project generation - but nowadays is more or less 
a standard because it's built-in into Visual studio and Qt. cmake dialect is bit difficult to learn and maintain.

2. [SCons project generation tool (Used within Godot game engine)](https://docs.godotengine.org/en/stable/development/compiling/introduction_to_the_buildsystem.html) Another project generation tool, written in Python. Advances over other project generation tools are mentioned on Godot web page.

## Make C++ Scriptable

*There are various attempts to make C++ scriptable*

1. [cling interactive C++ scripting](https://github.com/root-project/cling) [MIT]. Based on older LLVM/clang compiler (5.0) cling is command line tool for compiling and executing C++ directly.

  * Articles/Blogs:
    * [Interactive C++ with Cling](https://blog.llvm.org/posts/2020-11-30-interactive-cpp-with-cling/)

