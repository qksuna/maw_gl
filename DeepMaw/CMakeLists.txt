# CMakeList.txt : CMake project for DeepMaw, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.24)

project(DeepMaw)

# Add source to this project's executable.
add_executable (DeepMaw "DeepMaw.cpp" "DeepMaw.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET DeepMaw PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
