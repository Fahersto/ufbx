cmake_minimum_required(VERSION 3.16 FATAL_ERROR)

project ("viewer")



file(GLOB_RECURSE GAMEJAM_SOURCES LIST_DIRECTORIES true ../../ufbx.h ../../ufbx.c external.c viewer.c )

add_executable (viewer ${GAMEJAM_SOURCES})
