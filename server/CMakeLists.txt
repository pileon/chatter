set(SOURCE_FILES server.cpp)
add_executable(server ${SOURCE_FILES})
target_link_libraries(server common)
