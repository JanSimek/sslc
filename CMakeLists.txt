cmake_minimum_required(VERSION 3.5)

project(sslc
    VERSION 0.1
    DESCRIPTION "Script compiler for Fallout 2"
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(src)
