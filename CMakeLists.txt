cmake_minimum_required(VERSION 2.8)
project(desdelinux)

add_executable(desdelinux Main.cc DesdeLinux.cc)
install(TARGETS desdelinux DESTINATION bin)


