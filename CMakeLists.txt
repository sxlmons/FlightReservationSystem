cmake_minimum_required(VERSION 3.30)
project(AirlineReservationSystem C)

set(CMAKE_C_STANDARD 99)

add_executable(AirlineReservationSystem src/main.c
        src/creators.c
        include/creators.h
        src/data.c
        include/data.h
        src/interface.c
        include/interface.h
        src/seats.c
        include/seats.h
        src/sort.c
        include/sort.h)
