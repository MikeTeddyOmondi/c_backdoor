# C Backdoor
A simple malware written in C language.

It contains: 
---
1. server.c - where you will execute code to run on the target machine. Must be run on a Linux environment.
2. backdoor.c - which is the malware itself that will be executed on the target machine for gaining access and exploits. Runs only on Windows environment.
3. keylogger.h - is a header file that contains code that allows for logging keystrokes to a *.txt file.

Prerequisites:
---
- Install GCC Compiler for C/C++ [MingW(gcc-mingw-w64-i686)] on Linux so that you can compile the Windows executable for backdoor.c 
```bash
sudo apt-get install gcc-mingw-w64-i686 
```

# DISCLAIMER:
_Use with caution._ \
_Hack for fun not for profit._ \
**HACKING IS ILLEGAL!!!**