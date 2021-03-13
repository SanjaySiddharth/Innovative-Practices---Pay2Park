# cmake_minimum_required(VERSION <specify CMake version here>)
project(PAY2PARK)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(PAY2PARK
        Debug/.NETFramework,Version=v4.7.2.AssemblyAttributes.cpp
        main_view.cpp
        main_view.h
        SPLASH.cpp
        SPLASH.h)
