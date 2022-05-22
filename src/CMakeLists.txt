cmake_minimum_required(VERSION 3.18)

project(simplesql)

add_executable(
  ${PROJECT_NAME}
  main.c
)

install(
  TARGETS ${PROJECT_NAME}
  RUNTIME DESTINATION bin
)   
