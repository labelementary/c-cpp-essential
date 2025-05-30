cmake_minimum_required(VERSION 3.10)
   project(MyProject)

   # Set C++ standard
   set(CMAKE_CXX_STANDARD 11)
   set(CMAKE_CXX_STANDARD_REQUIRED True)

   # Add executable
   add_executable(MyExecutable src/main.c)

   # Include directories
   target_include_directories(MyExecutable PRIVATE include)