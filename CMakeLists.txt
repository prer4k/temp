cmake_minimum_required(VERSION 3.10)
project(BusReservationSystem)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

include_directories(include)

file(GLOB_RECURSE SRC "src/*.cpp")

add_executable(bus ${SRC})
