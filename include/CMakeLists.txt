cmake_minimum_required(VERSION 3.19)
project(AEndian)
add_library(AEndian INTERFACE)
target_sources(AEndian PRIVATE ABigEndian ALittleEndian)

