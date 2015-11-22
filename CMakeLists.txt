cmake_minimum_required(VERSION 3.3)
project(chatter LANGUAGES CXX)

add_compile_options(-std=c++1z -Wall -Wextra -Wpedantic -Weffc++)

# add_subdirectory(common)
add_subdirectory(client)
add_subdirectory(server)
