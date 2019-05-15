cmake_minimum_required(VERSION 3.12)

add_executable(my-main main.cpp)

set(install-dir E:\\Temp\\C++\\PointersAndReferences\\INSTALL)

set(install-path ${CMAKE_SOURCE_DIR}/install)

install(TARGETS my-main
        DESTINATION ${install-path}
)
