cmake_minimum_required(VERSION 3.16)
project(p0)

set(CMAKE_CXX_STANDARD 14)

include_directories(project-0-main)

add_executable(p0
        project-0-main/Book.cpp
        project-0-main/Book.h
        project-0-main/BookCreator.cpp
        project-0-main/BookCreator.h
        project-0-main/BookListCreator.cpp
        project-0-main/BookListCreator.h
        project-0-main/Info.cpp
        project-0-main/Info.h
        project-0-main/Library.cpp
        project-0-main/Library.h
        project-0-main/main.cpp)
