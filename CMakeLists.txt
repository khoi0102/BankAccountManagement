cmake_minimum_required(VERSION 3.28)
project(BankAccountManagement C)

set(CMAKE_C_STANDARD 11)

add_executable(BankAccountManagement main.c
        info.h
        info.c
        Acc.h
        Acc.c)
