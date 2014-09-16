cmake_policy(SET CMP0038 OLD)
cmake_policy(SET CMP0022 OLD)
set(CMAKE_TOOLCHAIN_FILE cmake/ArduinoToolchain.cmake) # Arduino Toolchain
cmake_minimum_required(VERSION 2.8)
project(Quad C CXX)
print_board_list()
print_programmer_list()
add_subdirectory(src)
