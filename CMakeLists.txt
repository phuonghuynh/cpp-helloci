cmake_minimum_required(VERSION 3.17)
project(cpp_hello)

set(CMAKE_CXX_STANDARD 14)


add_executable(main.cpp)

target_link_libraries(cpp_hello crypt32.lib)

