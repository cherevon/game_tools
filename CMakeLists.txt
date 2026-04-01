cmake_minimum_required(VERSION 3.27)

project("game_tools")

# Options
option(BUILD_SHARED_LIBS "Build using shared libraries" OFF)

# Add applications listed in this repository
add_subdirectory("app/minecraft/auto_clicker")
add_subdirectory("app/minecraft/auto_sell")
add_subdirectory("app/minecraft/gaia_killer")
add_subdirectory("app/rimworld/image_to_plan")