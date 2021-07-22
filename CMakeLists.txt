cmake_minimum_required(VERSION 3.19)
add_library(AEndian INTERFACE)
target_include_directories(AEndian INTERFACE
  $<BUILD_INTERFACE:${CMAKE_CURRENT_LIST_DIR}/include>
  $<INSTALL_INTERFACE:include/AEndian>  # <prefix>/include/mylib
)
message("AEndian included")
