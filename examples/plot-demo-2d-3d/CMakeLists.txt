##########################################################################

cmake_minimum_required (VERSION 2.8)

##########################################################################

set(TARGET plot-demo-2d-3d)

##########################################################################

add_executable(
  ${TARGET} 
  main.cpp
)

target_link_libraries(
  ${TARGET} 
  plot
)

##########################################################################

