# SPDX-FileCopyrightText: 2023 Pablo Portas López <pablo.portas@udc.es>
#
# SPDX-License-Identifier: GPL-3.0-only

cmake_minimum_required(VERSION 3.22) # Esta versión del CMake es la de Ubuntu 22.04 LTS
project(Pro2324 C)

set(CMAKE_C_STANDARD 99)

# Por defecto
add_executable(Pro2324 src/main.c)
# Boletín 1
add_subdirectory(./src/Boletin_1)
# Boletín 2
add_subdirectory(./src/Boletin_2)
# Boletín 3
add_subdirectory(./src/Boletin_3)
# Boletín 4
add_subdirectory(./src/Boletin_4)
# Ejemplos (Antiguamente Prácticas)
add_subdirectory(./src/Ejemplos)
# Extras
add_subdirectory(./src/Extras)
# Exámenes
add_subdirectory(./src/Examenes)