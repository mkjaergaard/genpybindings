cmake_minimum_required(VERSION 2.8)
project(genpy_boost)

find_package(catkin)

#find_package(Boost COMPONENTS python)
#include_directories(${Boost_INCLUDE_DIRS})

#FIND_PACKAGE(PythonLibs)
#INCLUDE_DIRECTORIES(${PYTHON_INCLUDE_PATH})

#add_library(std_msgs SHARED src/string.cpp)
#SET_TARGET_PROPERTIES(std_msgs PROPERTIES PREFIX "")
#target_link_libraries(std_msgs ${Boost_LIBRARIES})

install_cmake_infrastructure(genpy_boost
  VERSION 0.0.0
  CFG_EXTRAS genpy_boost-extras.cmake
  )

catkin_package(genpy_boost)