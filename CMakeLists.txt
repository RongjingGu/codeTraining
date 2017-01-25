# cmake_minimum_required(VERSION <specify CMake version here>)
project(codeTraining)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        .gitignore
        README.md core/sum_1.cpp)

add_executable(codeTraining ${SOURCE_FILES})