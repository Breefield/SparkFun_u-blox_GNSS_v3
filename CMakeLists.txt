# CMakeFiles.txt inside "SparkFun_u-blox_GNSS" folder
cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "src/u-blox_GNSS.cpp" "src/sfe_bus.cpp"
        INCLUDE_DIRS "src/."
        REQUIRES arduino-esp32 Adafruit_BusIO)

project(SparkFun_u-blox_GNSS)
