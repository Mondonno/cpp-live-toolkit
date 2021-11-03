# C++ Live Toolkit

CLT (C++ Live Toolkit) is subset of tools that are very light in size, and maintained to help programmers in compiling and executing C++ code in the fly.

If you appriciate this project contribute to it by hitting ⭐️

## List of tools

- **C++ ReplY**: 
    C++ fast and light in size repl program that helps to compile ideas in the file without creating useless files.
- **C++ Liver**:
    Live is a program that monitor changes on your files and compiles them and runs automatically, without any interaction.

### Documentation

Here is documentated usage and compilation of tools mentioned in the list above.

#### C++ Live Compile Repl

To use repl compile `src/toolkit/repl.cpp`.
After that run it, you will get something like this:
```
CLT C++ LRC Live Repl Compiler

cpp >> 
```
<br>

There are 2 directives included: 
- `#include<iostream>`
- `#include<cmath>`
<br>

Just type your code into it and results will show up automatically.
There is also subset of extra commands.

- **.help**
    Standard help message
- **.quit** 
    Quit the repl
- **.clear**: 
    Clears up the code cached in the variable.
- **.include every_directive**
    You can add by it every directive what you need
- **.run**
    Runs constructed c++ code

#### C++ Liver

To use live compile `src/toolkit/live.cpp`
Syntax of the live program is: `./name_of_executable name_of_file.cpp`

It will listen on changes in the file/files.
Liver will compile and run your code on every edit.

You can also include more files!
`./name_of_executable name_of_file_1.cpp name_of_file_2.cpp name_of_file_3.cpp name_of_file_4.cpp ... name_of_file_n.cpp`