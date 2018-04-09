cmake_minimum_required(VERSION 3.10)
project(RealTimeSystem)

set(CMAKE_CXX_STANDARD 17)
include_directories(Plugins/TinyXML)
add_executable(RealTimeSystem main.cpp Plugins/TinyXML/tinyxml2.h Plugins/TinyXML/tinyxml2.cpp )