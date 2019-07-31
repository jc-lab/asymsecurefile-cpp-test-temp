cmake_minimum_required(VERSION 3.14)
project(asymsecurefile_test)

set(CMAKE_CXX_STANDARD 11)

add_executable(asymsecurefile_test main.cpp)

include_directories(.)
include_directories(mbedtls-apache-prebuilt-winx86/include)
include_directories(openssl-prebuilt-winx86/include)