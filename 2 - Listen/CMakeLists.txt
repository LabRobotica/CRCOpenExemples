cmake_minimum_required(VERSION 2.8.0)
project(eORL)

set(CMAKE_BUILD_TYPE Release)
set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -g -Wall")
set(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -O2")


include_directories(include /opt/inc)


add_executable(main
main.c
)

add_library(eorl SHARED IMPORTED)
set_property(TARGET eorl PROPERTY IMPORTED_LOCATION /opt/lib/libeORL.so)

target_link_libraries(main eorl m pthread)
