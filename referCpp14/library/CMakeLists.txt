CMAKE_MINIMUM_REQUIRED(VERSION 3.5)
PROJECT(LIBRARY)
SET(CMAKE_CXX_STANDARD 14)
ADD_DEFINITIONS("-fno-elide-constructors")
MESSAGE(STAUTS  "this is a binary dir ", ${LIBRARY_BINARY_DIR})
MESSAGE(STAUTS  "this is a source dir ", ${LIBRARY_SOURCE_DIR})
ADD_SUBDIRECTORY(src bin)

