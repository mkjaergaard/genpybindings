cmake_minimum_required(VERSION 2.8)
project(genpybindings)

find_package(catkin)

install_cmake_infrastructure(genpybindings
  VERSION 0.0.0
  CFG_EXTRAS genpybindings-extras.cmake
  )

catkin_package(genpybindings)