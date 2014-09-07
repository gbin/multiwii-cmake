set(ARDUINO_DEFAULT_BOARD mega2560)
set(ARDUINO_DEFAULT_PORT /dev/ttyUSB0)

generate_arduino_firmware(quad
  SRCS Alarms.cpp  GPS.cpp LCD.cpp Output.cpp RX.cpp Serial.cpp EEPROM.cpp IMU.cpp MultiWii.cpp Protocol.cpp Sensors.cpp
  )
