#Defined project name
project(2P11)

#Assign Modules path
set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${CMAKE_SOURCE_DIR}/cmake/Modules/")

#Defined project VERSION
set(VERSION_MAJOR 0)
set(VERSION_MINOR 1)
set(VERSION_REV 0)
set(VERSION "${VERSION_MAJOR}.${VERSION_MINOR}.${VERSION_REV}")

#Minimum cmake VERSION
cmake_minimum_required(VERSION 2.6)

#Add source directory
add_subdirectory(src)

