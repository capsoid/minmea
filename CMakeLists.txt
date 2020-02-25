cmake_minimum_required(VERSION 3.16.1)

project(minmea VERSION 1.0 LANGUAGES C)

add_library(minmea STATIC
    minmea.c
    minmea.h
    )
