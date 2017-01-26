cmake_minimum_required(VERSION 3.6)
project(SocketProject)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c echo_client.c echo_server.c)
add_executable(SocketProject ${SOURCE_FILES})