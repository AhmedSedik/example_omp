cmake_minimum_required(VERSION 3.20)
project(untitled5)

set(CMAKE_CXX_STANDARD 14)

add_executable(untitled5 main.cpp)

cmake_minimum_required(VERSION 3.6)
project(openmp_test_clion)

# added -fopenmp
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -fopenmp")

set(SOURCE_FILES main.cpp pi/pi.cpp)
add_executable(openmp_test_clion ${SOURCE_FILES})