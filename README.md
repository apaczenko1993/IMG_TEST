Attempt to flash LVGL to Waveshare ESP32-S3 LCD Touch 7
Link to display:
https://www.waveshare.com/wiki/ESP32-S3-Touch-LCD-7

The project contains a simple LVGL UI with 2 images but under compiling i receive error:

Creating esp32s3 image...

Merged 2 ELF sections

Successfully created esp32s3 image.

Generated C:/Projekty/ESP-IDE/IMG_TEST/build/IMG_TEST.bin
[1389/1389] cmd.exe /C "cd /D C:\Projekty\ESP-IDE\IMG_TEST\build\esp-idf\esptool_py && python C:/Espressif/frameworks/esp-idf-v5.3.1/components/partition_table/check_sizes.py --offset 0x8000 partition --type app C:/Projekty/ESP-IDE/IMG_TEST/build/partition_table/partition-table.bin C:/Projekty/ESP-IDE/IMG_TEST/build/IMG_TEST.bin"
FAILED: esp-idf/esptool_py/CMakeFiles/app_check_size C:/Projekty/ESP-IDE/IMG_TEST/build/esp-idf/esptool_py/CMakeFiles/app_check_size 
cmd.exe /C "cd /D C:\Projekty\ESP-IDE\IMG_TEST\build\esp-idf\esptool_py && python C:/Espressif/frameworks/esp-idf-v5.3.1/components/partition_table/check_sizes.py --offset 0x8000 partition --type app C:/Projekty/ESP-IDE/IMG_TEST/build/partition_table/partition-table.bin C:/Projekty/ESP-IDE/IMG_TEST/build/IMG_TEST.bin"
Error: app partition is too small for binary IMG_TEST.bin size 0x1f7110:

  - Part 'factory' 0/0 @ 0x10000 size 0x100000 (overflow 0xf7110)

ninja: build stopped: subcommand failed.



