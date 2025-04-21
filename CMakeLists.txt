cmake_minimum_required(VERSION 3.10)

# Set the project name
project(Sift)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add an executable
file(GLOB SOURCES sift.cpp includes/*.cpp)
add_executable(sift ${SOURCES}) 