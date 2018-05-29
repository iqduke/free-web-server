cmake_minimum_required(VERSION 3.10)
project(free_web_server)

set(CMAKE_CXX_STANDARD 11)

add_executable(free_web_server
        .gitignore
        LICENSE
        README.md src/main.cpp)
