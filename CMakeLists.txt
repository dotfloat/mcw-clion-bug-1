cmake_minimum_required(VERSION 3.10)
project(mcw-clion-bug-1)

add_executable(mcw-clion-bug-1 src/main.cc)
target_include_directories(mcw-clion-bug-1 PRIVATE include)