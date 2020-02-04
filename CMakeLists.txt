cmake_minimum_required(VERSION 3.10)

# set the project name and version
project(LearnCpp VERSION 1.0.0)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(learn-cpp main.cpp)
add_executable(cxx17-test cxx17Test.cpp)