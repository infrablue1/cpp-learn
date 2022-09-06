

SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})
add_executable(test_math test_math.cc)
target_link_libraries(test_math mylib)
