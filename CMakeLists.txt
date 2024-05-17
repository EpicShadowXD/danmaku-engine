cmake_minimum_required(VERSION 3.1...3.29)
project(engine)

set(CMAKE_CXX_COMPILER g++-13)

set(SOURCES
  src/main.cpp)

set(HEADERS

)

include_directories(include)

add_executable(engine ${SOURCES} ${HEADERS})