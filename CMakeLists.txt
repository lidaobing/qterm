project( qterm )
cmake_minimum_required( VERSION 2.4.2 FATAL_ERROR )
set( CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake" )
find_package( Qt4 REQUIRED )
find_package( OpenSSL REQUIRED )
add_subdirectory( src )