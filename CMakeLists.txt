cmake_minimum_required(VERSION 3.3)
project(Simple_Translator)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    lexer.cpp
    lexer.h
    parser.cpp
    parser.h
    README.md)

add_executable(Simple_Translator ${SOURCE_FILES})