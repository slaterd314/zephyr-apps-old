# Copyright (c) 2023 Teledatics, Inc.
# All Rights Reserved
#
# This CMake file is picked by the Zephyr build system because it is defined
# as the module CMake entry point (see zephyr/module.yml).

zephyr_include_directories(include)

add_subdirectory(drivers)
add_subdirectory(lib)
