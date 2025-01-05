cmake_minimum_required(VERSION 3.27)
project(IndexedList_fr)

set(CMAKE_CXX_STANDARD 17)

add_executable(IndexedList_fr
        App.cpp
        ExtendedTest.cpp
        ExtendedTest.h
        IndexedList.cpp
        IndexedList.h
        ListIterator.cpp
        ListIterator.h
        ShortTest.cpp
        ShortTest.h)
