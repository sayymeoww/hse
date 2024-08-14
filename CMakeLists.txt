cmake_minimum_required(VERSION 3.20.6)
project(hse)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS_INIT "-Wall -O3 -std=c++20 -Wextra -Wpedantic -Wshadow -Wconversion -Wsign-conversion -Wcast-align -Wcast-qual -Wnull-dereference -Woverloaded-virtual -Wformat=2 -Werror")

add_executable(main main.cpp)
