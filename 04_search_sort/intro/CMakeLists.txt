cmake_minimum_required(VERSION 3.8)  # CMake version check
project(search_sort)               # Create project "simple_example"
set(CMAKE_CXX_STANDARD 17)            # Enable c++14 standard

# Add main.cpp file of project root directory as source file
set(sort_prog.cpp main.cpp)

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(search_sort ${sort_prog.cpp})