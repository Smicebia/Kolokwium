cmake_minimum_required (VERSION 3.8)
project (myProgram)
include_directories(Include)
file(GLOB SOURCES "src/*.cpp")
add_executable(myProgram ${SOURCES})
install(DIRECTORY src DESTINATION build)


