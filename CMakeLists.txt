cmake_minimum_required(VERSION 3.6)
project(asio_ddos_protector)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(asio_ddos_protector ${SOURCE_FILES})