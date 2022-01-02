cmake_minimum_required(VERSION 3.20.0)

find_package(Zephyr)

project(k2_firmware)

target_sources(app PRIVATE src/main.c)
