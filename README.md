# awesome-c-basics

A list of tools and libraries for people and developers just starting out in C.

---

Below is a list of my favorite websites and tools for C programming development!

| Name | About | Section Link |
| :--- | :--- | :--- |
| Visual Studio | An advanced programming environment by Microsoft. | [Jump to Section](#visual-studio) |
| libc | The standard C libraries for input/output and core functions. | [Jump to Section](#libc) |
| W3Schools | A C tutorial to help guide you through the basics. | [External Link](https://www.w3schools.com/c/index.php) |

---

## Visual Studio

Visual Studio is an advanced programming environment by Microsoft. It is quite good in my experience because when you load the installer and select **"Desktop development with C++[^note]"** you can customize your C programming environment.

By installing this, you get the four essential parts of the Microsoft C Runtime:
1. **UCRT:** The Universal C Runtime (Standard C functions).
2. **vcruntime:** Compiler-specific support code.
3. **CRT Startup:** The hidden code that prepares your `main()` function.
4. **msvcprt:** Necessary C++ base support for the toolset.

To install it [follow this link!](https://visualstudio.microsoft.com/)

---

## libc

`libc` is the standard library for the C programming language. It is the foundation that provides essential headers like `<stdio.h>`, `<stdlib.h>`, and `<unistd.h>`[^1] (for Linux/macOS users). 

It acts as the bridge between your code and the operating system, allowing your programs to:
* **Interact with users** (printing text or reading keyboard input).
* **Manage memory** (allocating space for data like `malloc`).
* **Talk to the Filesystem** (opening and saving files).



---

## Footnotes
[^note]: **Minimal Install Guide:** To save disk space, only select: **"MSVC Build Tools x64/86 (Latest)"**, **"C++ Profiling Tools"**, **"IntelliCode"**, and the **"Windows 11 SDK"**. This provides all the core parts of the runtime without the massive extra weight of unnecessary C++ libraries.
[^1]: `unistd.h` is the header name for the POSIX operating system API, standard on Linux and macOS but not natively part of MSVC on Windows.
