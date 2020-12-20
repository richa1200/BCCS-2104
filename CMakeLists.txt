cmake_minimum_required(VERSION 3.17)
project(BCCS_2104)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(BCCS_2104
        bill.h
        customer.h
        item.h
        main.cpp
        reception.h
        manager.h item.cpp reception.cpp bill.cpp)
