CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

include(RezBuild)

subdirs(lib)
subdirs(util)

MESSAGE( STATUS "PATH:         " $ENV{PATH} )

