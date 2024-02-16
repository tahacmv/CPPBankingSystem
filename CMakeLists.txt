cmake_minimum_required(VERSION 3.27)
project(CPPBankingSystem)

set(CMAKE_CXX_STANDARD 17)

add_executable(CPPBankingSystem src/main.cpp
        test/test.cpp
        test/test.h)
