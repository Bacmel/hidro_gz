cmake_minimum_required(VERSION 3.10.2 FATAL_ERROR)
project(odri_joint_controller VERSION 0.0)

find_package(ignition-cmake2 2.12.0 REQUIRED)

find_package(ignition-plugin1 REQUIRED COMPONENTS register)

find_package(ignition-gazebo6 REQUIRED)
find_package(ignition-msgs8 REQUIRED)

find_package(Protobuf REQUIRED)

