cmake_minimum_required(VERSION 3.0)
project(try_server)

set(CMAKE_CXX_STANDARD 14)

add_executable(try_server main.cpp server/server.c)