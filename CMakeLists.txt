cmake_minimum_required(VERSION 3.8)

project(vulkanhpp LANGUAGES CXX)

add_library(vulkanhpp INTERFACE)

target_include_directories(include/vulkan/vulkan.hpp)
