cmake_minimum_required(VERSION 3.21)
project(BBANK)

set(CMAKE_CXX_STANDARD 23)

add_executable(BBANK main.cpp BANKS.cpp BANKS.h ATMScreens.cpp ATMScreens.h)
