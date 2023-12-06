cmake_minimum_required(VERSION 3.10)
project(cpp-sample)

# Definir la versión del lenguaje C++
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Agregar el ejecutable generado a partir de main.cpp
add_executable(cpp-sample src/main.cpp)
