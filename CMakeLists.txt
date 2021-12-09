cmake_minimum_required(VERSION 3.20)
project(4k)

set(CMAKE_CXX_STANDARD 20)
add_subdirectory(extern/atto)
add_executable(4k tool.cc)
target_link_libraries(4k PRIVATE atto)


