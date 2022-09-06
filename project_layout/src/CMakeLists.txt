


SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})
add_library(mylib STATIC mymath.cc)
add_executable(${PROJECT_NAME} main.cc)
target_link_libraries(${PROJECT_NAME} mylib)
link_directories(lib)