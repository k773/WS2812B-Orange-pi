cmake_minimum_required(VERSION 3.14)
project(W2812Clock)

set(CMAKE_CXX_STANDARD 14)

add_executable(W2812Clock main.cpp ws2812b/RGB.h ws2812b/Led.cpp ws2812b/Led.h spi/SPI.cpp spi/SPI.h)
target_link_libraries(W2812Clock)
