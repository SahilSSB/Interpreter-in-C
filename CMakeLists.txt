cmake_minimum_required(VERSION 3.15)
project(Interpreter-in-C)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(Interpreter-in-C
  main.c
  chunk.c
  memory.c
  debug.c
  value.c
  vm.c
  compiler.c
  scanner.c
  object.c
)
