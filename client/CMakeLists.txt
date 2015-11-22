set(SOURCE_FILES client.cpp)
add_executable(client ${SOURCE_FILES})
target_link_libraries(client common)
