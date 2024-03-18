# CMakeList.txt : CMake project for dbench_jumbf_app, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (dbench_jumbf_app "dbench_jumbf_app.cpp" "dbench_jumbf_app.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET dbench_jumbf_app PROPERTY CXX_STANDARD 14)
endif()

# TODO: Add tests and install targets if needed.
