cmake_minimum_required(VERSION 3.9)
project(apppimage-desktop-integration)

set(CMAKE_CXX_STANDARD 11)

add_subdirectory(src)

include(pack/cpack_debs.cmake)