add_compile_options(-Wno-error) # You might have this line from before
cmake_minimum_required(VERSION 3.5)
include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(wifi_eth_bridge_wt32)
idf_build_set_property(REQUIRES esp_eth) # <--- ADD THIS LINE