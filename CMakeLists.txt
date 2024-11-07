cmake_minimum_required(VERSION 3.6)
project(thread-pool)

add_library(thread-pool INTERFACE)
target_include_directories(thread-pool INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
