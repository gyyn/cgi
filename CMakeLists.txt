cmake_minimum_required(VERSION 3.14)
project(cgi)

set(CMAKE_CXX_STANDARD 17)

add_executable(cgi cgi.cpp processpool.h)