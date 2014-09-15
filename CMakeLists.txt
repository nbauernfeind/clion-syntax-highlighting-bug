cmake_minimum_required(VERSION 2.8.4)
project(sample)

set(CMAKE_CXX_FLAGS "-include ${PROJECT_SOURCE_DIR}/incHeader.h")
set(SOURCE_FILES main.cpp)
set(HEADER_FILES incHeader.h)
add_executable(sample ${SOURCE_FILES} ${HEADER_FILES})