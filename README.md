## C++ Live Toolkit

CLT (C++ Live Toolkit) is subset of tools that are very light in size, and maintained to help programmers in compiling and executing C++ code in the fly.

If you appriciate this project contribute to it by hitting ⭐️

### List of tools

Here are listed tools that are inside toolkit.<br>
If you have idea related to this project, consider contributing.

- **C++ Live Compile Repl (C++ LCP)**:<br>
    Cpp fast and light in size repl program that helps to compile ideas in the file without creating useless files.
    <br>
- **C++ Liver**:<br>
    Live is a program that monitor changes on your files and compiles them and runs automatically, without any interaction.
    <br>

### C++ LCP

To use repl compile `src/toolkit/repl.cpp`.
After that, run it, you will get something like this:
```
CLT C++ LRC Live Repl Compiler

cpp >> 
```

There are two directives included: 
- `#include<iostream>`
- `#include<cmath>`


Just type your code into it and results will show up automatically.

**Avaible commands**

- **.help**<br>
    Standard help message
- **.quit**<br>
    Quit the repl
- **.clear**<br>
    Clears up the code cached in the variable.
- **.include `every_directive`**<br>
    You can add by it every directive what you need
- **.run**<br>
    Runs constructed c++ code

### C++ Liver

To use live compile `src/toolkit/live.cpp`<br>
Syntax of the live program is: `./name_of_executable name_of_file.cpp`<br>

It will listen on changes in the file/files.<br>
Liver will compile and run your code on every edit.<br>

You can also include more files!<br>
`./name_of_executable name_of_file_1.cpp name_of_file_2.cpp name_of_file_3.cpp name_of_file_4.cpp ... name_of_file_n.cpp`