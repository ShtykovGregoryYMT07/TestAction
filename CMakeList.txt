cmake_minimum_required(VERSION 2.8.9)
project (hello)
find_package(Boost COMPONENTS unit_test_framework REQUIRED)
add_executable(hello main.cpp)