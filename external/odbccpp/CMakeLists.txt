CMAKE_MINIMUM_REQUIRED(VERSION 3.10)

SET(CMAKE_CXX_STANDARD 11)

PROJECT(odbccpp)

FIND_PACKAGE(ODBC REQUIRED)

ADD_SUBDIRECTORY(src)

