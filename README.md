# Firmware_binary
Esptool.py --port /dev/ttyUSB0 --baud 460800 write_flash --flash_size=detect -fm dio 0 airrohr-firmware/.pio/build/nodemcuv2_en/firmware.bin

esptool.py --port /dev/ttyUSB0 erase_flash
