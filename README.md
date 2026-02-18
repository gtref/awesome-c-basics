# Awesome C Basics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A list of tools and libraries for people and developers just starting out in C.

## Contents

- [Visual Studio](#visual-studio)
- [Standard Libraries](#standard-libraries)
- [Learning Resources](#learning-resources)

## Visual Studio

- [Visual Studio](https://visualstudio.microsoft.com/) - Advanced programming environment by Microsoft that allows a customized C environment by selecting "Desktop development with C++". 

For a minimal installation to save disk space, select only "MSVC Build Tools x64/86 (Latest)", "C++ Profiling Tools", "IntelliCode", and the "Windows 11 SDK". This provides the core parts of the runtime without unnecessary weight.

By installing this, you get the four essential parts of the Microsoft C Runtime:

* **UCRT:** The Universal C Runtime for standard C functions.
* **vcruntime:** Compiler-specific support code.
* **CRT Startup:** The code that prepares your `main()` function.
* **msvcprt:** Necessary C++ base support for the toolset.

## Standard Libraries

- [libc](https://www.gnu.org/software/libc/) - Standard library foundation that provides essential headers like `<stdio.h>`, `<stdlib.h>`, and `<unistd.h>`. 

Note that `unistd.h` is the header name for the POSIX operating system API, which is standard on Linux and macOS but not natively part of MSVC on Windows. These libraries allow your programs to:

* Interact with users by printing text or reading input.
* Manage memory by allocating space using functions like `malloc`.
* Talk to the filesystem to open and save files.

## Learning Resources

- [W3Schools](https://www.w3schools.com/c/index.php) - Comprehensive C tutorial designed to guide beginners through the basics.

## License

This project is licensed under the MIT License.
