cmake_minimum_required(VERSION 3.5.0)
project(Complex)

set(SOURCES
       
    ./src/complex.h
    ./src/complex.cpp

    )

include_directories(
    ./src/
    )
add_executable(Complex ./main.cpp ${SOURCES})
