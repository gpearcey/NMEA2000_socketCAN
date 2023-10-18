add_library(
    NMEA2000_socketCAN SHARED
    NMEA2000_SocketCAN.cpp
    NMEA2000_SocketCAN.h
)

target_link_libraries(NMEA2000_socketCAN PUBLIC nmea2000)
