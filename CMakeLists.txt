cmake_minimum_required(VERSION 3.9)
project(sonarqube_ccode_project)

# Set C++ standard to C++17
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(sonarqube_ccode_project src/main.cpp)


