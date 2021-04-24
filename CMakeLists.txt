PROJECT(example-project)

CMAKE_MINIMUM_REQUIRED(VERSION 3.10)

set (CMAKE_CXX_STANDARD 11)

add_subdirectory(sub_project)
add_executable(main1 main.cpp)
