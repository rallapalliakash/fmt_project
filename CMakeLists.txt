cmake_minimum_required(VERSION 3.15)

project(FmtExample)

add_executable(app src/main.cpp)

find_package(fmt REQUIRED)

target_link_libraries(app fmt::fmt)