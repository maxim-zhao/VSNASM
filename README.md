VSNASM NuGet package
=============

See [VSNASM](https://github.com/ShiftMediaProject/VSNASM/releases) for the original.

## About

VSNASM provides a set of build customisations that can be used within Visual Studio to compile assembly code using NASM.

This fork adds NuGet packaging.

## NASM

The Netwide Assembler (NASM) is an assembler and disassembler for the Intel x86 architecture. It can be used to write 16-bit, 32-bit (IA-32) and 64-bit (x86-64) programs.
For more information on NASM refer to the official site: [www.nasm.us](www.nasm.us).

## Installation

Add "VSNASM" as a dependency to your project in the NuGet Package Manager.

The project provides a basic installer script that can automatically detec

To assemble a file with NASM, select the Property Page for the file and ensure that 'Nasm Assembler' is selected in the Tool dialog entry.

The additional NASM property page can then be used to change various options supported by NASM.