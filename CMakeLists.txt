cmake_minimum_required(VERSION "3.8")

project(
  "minecraft-cxx"

  LANGUAGES
  "C" "CXX" "ASM"
)

set(CMAKE_CXX_STANDARD "20")
set(CMAKE_C_STANDARD "11")

add_subdirectory("minecraft")
