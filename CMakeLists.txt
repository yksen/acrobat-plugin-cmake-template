cmake_minimum_required(VERSION 3.20)
project(acrobat-plugin-cmake-template)

add_definitions(-DWIN_ENV=1 -DWIN_PLATFORM=1 -DWIN32=1 -DWINDOWS=1)

add_subdirectory(lib)
add_subdirectory(src)
