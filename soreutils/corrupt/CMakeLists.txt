CMAKE_MINIMUM_REQUIRED(VERSION 3.0)
PROJECT(corrupt)
ADD_EXECUTABLE(corrupt corrupt.c)
TARGET_LINK_LIBRARIES(corrupt m)
INSTALL(TARGETS corrupt DESTINATION bin)
