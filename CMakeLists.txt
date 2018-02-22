cmake_minimum_required(VERSION 3.9)
project(name_entities)

set(CMAKE_CXX_STANDARD 11)

include(/home/giulia/Scaricati/MITIE-master/mitielib/cmake)

add_executable(name_entities main.cpp Histogram.cpp Histogram.h StringAdjuster.cpp StringAdjuster.h)

TARGET_LINK_LIBRARIES(name_entities mitie)