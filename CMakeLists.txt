if(NOT WIN32)
  add_definitions(-std=c++11)
endif()


cmake_minimum_required(VERSION 3.5)
project(ariac_environment)


find_package(rosidl_default_generators REQUIRED)


find_package(ament_cmake REQUIRED)

ament_package()
