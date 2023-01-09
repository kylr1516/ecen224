---
title: Coding Standard
layout: page
icon: fa-duotone fa-terminal
---

We decided to keep the coding standard simple so you can worry less about the standard and more about learning. The coding standard has the following requirements:

1. All code must be written in C.
  
2. You must use [ClangFormat](https://clang.llvm.org/docs/ClangFormat.html) to format your code with the following options: 
  ```
  { BasedOnStyle: LLVM, UseTab: Never, IndentWidth: 4, TabWidth: 4, ColumnLimit: 100, InsertBraces: true }
  ```
  We will show you how to use this in one of your labs. Set it up to run on save.

3. For every function you write, have a block comment before it explaining what the function does.
