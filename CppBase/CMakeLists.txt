# cmake_minimum_required(VERSION <specify CMake version here>)
project(CppBase)

set(CMAKE_CXX_STANDARD 11)

add_executable(CppBase main.cpp c_base/header_sample.h c_base/header_sample.cpp cpp_base/oop/Animal.cpp cpp_base/oop/Animal.h)