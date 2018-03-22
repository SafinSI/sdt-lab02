cmake_minimum_required(VERSION 3.7)
project(RepoA)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_EXE_LINKER_FLAGS -static)
set(SOURCE_FILES main.cpp)
add_executable(RepoA ${SOURCE_FILES})