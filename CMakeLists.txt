cmake_minimum_required(VERSION 3.0)
project(adios2_cmake_bug)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/Modules")

#include(MyThirdParty)

find_package(ADIOS2 REQUIRED)

include(MyThirdParty)

