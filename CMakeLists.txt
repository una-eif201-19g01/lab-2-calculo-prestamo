cmake_minimum_required(VERSION 3.14)
project(lab_2_calculo_prestamo)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(lab_2_calculo_prestamo
        CalculoPrestamo.cpp
        CalculoPrestamo.h
        main.cpp)
