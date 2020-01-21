cmake_minimum_required(VERSION 3.1)
project(BlitLander)
include(libs/32blit-beta/32blit.cmake)
blit_executable(lander src/lander.cpp)
