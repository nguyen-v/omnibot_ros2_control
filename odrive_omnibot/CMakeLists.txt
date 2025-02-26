cmake_minimum_required(VERSION 3.8)
project(odrive_omnibot)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY description/urdf config launch
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
