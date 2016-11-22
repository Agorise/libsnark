cmake_minimum_required (VERSION 2.6)
project (snark)

include_directories("${GMT_INCLUDE_DIR}")
include_directories("${SODIUM_INCLUDE_DIR}")
include_directories ("${PROJECT_SOURCE_DIR}/src")
add_subdirectory ("src") 
