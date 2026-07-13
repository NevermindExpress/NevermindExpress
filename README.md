I do software. I work on Windows NT and Win32, networking, low-level machine code, UEFI, and operating systems development. I primarily write in C/C++. There’s not much else you need to know about me.

# Works and Projects

*List is not exhaustive. Entries without links are either not mature enough to be shared or are archived.*

## Windows NT and Win32
- [TimeDefuser](https://github.com/NevermindExpress/TimeDefuser): Security research on expiration date (timebomb) enforcement in the Windows NT kernel, with a PoC implementation that bypasses it.
- [rundll64](https://github.com/NevermindExpress/rundll64): Arbitrary DLL procedure calling utility inspired by `rundll32`, extended to support calling functions with arbitrary signatures.

## Networking
- **Clara Server:** A high-performance networking server framework implementing native primitives of each platform (IOCP on Windows, kqueue on BSD, etc.). Designed to remove the learning curve of advanced networking and allow developers to focus on protocol implementation. *Work in progress.*
- [Alyssa HTTP Server](https://github.com/NevermindExpress/AlyssaHTTPServer): An HTTP server implementing HTTP/2, chunked encoding, CGI, and more. One of my earliest projects; currently archived but may be revived as a Clara module.
- *SimpleChat:* A simple chat application. My first real project (2022). Archived.

## General User-space
- **Ardipithecus:** A cross-platform lightweight GUI library for building applications entirely in code, supporting both anchored and manual layouts. *Work in progress.*

## UEFI and Operating Systems
- [efi.h](https://github.com/NevermindExpress/efi.h): Simple amalgamation UEFI development library, without any build systems or extra code
- **Stacey UEFI Operating Environment:** A UEFI-based operating environment (similar in concept to how Windows 9x sits on DOS) for basic computing and system recovery. Features cooperative multitasking and its own API/runtime. *Early work in progress.*
- **Tracey Operating System:** A Windows NT-like (not a strict clone) operating system aiming for user-space compatibility with Windows. *Even earlier work in progress.*

## Compilers, assemblers, and other things that converts text to machine code
- **Aceyware Verifying C/C++ Compiler** (codenamed *Shirley*): A modular C/C++ compiler that analyzes safety of the code and disallows unsafe code, as a proof that rust is not the solution. *Work in progress (Standard library essentials are done, linker is half-done)*

## Games
- **Milestones 3000:** A card-based racing game. *Work in progress.*

<sub>Read the notice about my username change in 2025 [here](https://github.com/NevermindExpress/NevermindExpress/blob/master/Username-change.md)</sub>

<sub>Comments or complains? [They go here](https://github.com/NevermindExpress/NevermindExpress/issues) or contact me from one of the comms addresses listed in left.</sub>
