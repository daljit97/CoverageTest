cmake_minimum_required(VERSION 3.20)

project(Test)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Test main.cpp lib.h)

include(CTest)

# add tests
add_test(NAME Test COMMAND Test)
