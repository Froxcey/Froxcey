# Language Tiers

**DISCLAIMER: THIS IS NOT RANKING OF GOOD AND BAD OF LANGUAGES!**

Different languages trade simplicity of resource management with performance, and this tier list simply categorizes languages based on features of their implementations. A well written JIT app can run faster than a poorly written assembly code. Languages are only tools, and theoretical performance is not everything. The languages in each categories are not listed in any particular order. I ain't expert in every language, so please let me know if I made a mistake.

## S: Machine code

Languages in this tier has 1:1 relation between written instructions and CPU operations 

- Assembly
- WASM

## A: Native

Languages in this tier allows developers to have complete control over memory management

- C
- C++
- Zig
- Mojo
- Rust
- Nim
- Odin
- Fortran

## B: Garbage collected

Languages in this tier can be compiled to machine code but has a runtime to manage the memory

- Golang
- Swift
- OCaml
- Gleam
- Dart
- Haskell
- C#
- ObjC
- COBOL
- Pascal

## C: Bytecode

Languages in this tier requires compilation into bytecode with a runtime interpreter

- JVM Based
  - Java
  - Kotlin
  - Closure
  - Scala
- Erlang
- Elixir

## D+: Embedded JIT

Languages in this tier are JIT with the primary purpose of being embedded into other applications

- JavaScript
  - TypeScript
  - CoffeeScript
- Lua
- Julia

## D: JIT

Languages in this tier are JIT with the primary purpose of scripting

- Python
- Ruby
- PHP
- HolyC
- Perl
- Common Lisp

## D-: Interpreted

Lanaguages in this tier needs JIT

- ShellScript

## F: Esoteric

Languages that are big brain

- Brainf**k
- Malbolge
