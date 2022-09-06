cmake_minimum_required(VERSION 3.16)
#set the project name 
project(project_layout)

set(CMAKE_CXX_STANDARD 17)
include_directories(src)

#加入警告信息或者一些其他的编译参数
add_definitions(-Wall -g)
set(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib)

add_subdirectory(src)
add_subdirectory(test)

link_directories(lib)