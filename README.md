# ESP32 SD card demo using alternative SPI (HSPI) port
Intended as a bare-bones for use on TTGO T-Beam, due to VSPI being already allocated to on-board devices.

##  Hardware:
* Generic ESP32 DevKit board
* SD card breakout board (3.3v minimal component version, all passive components, will probably work OK on others)
* Using PlatformIO

##  Credits:
* Used as a base for SD card read/write testing using Arduino FS module https://RandomNerdTutorials.com/esp32-microsd-card-arduino/
* Hints for switching to HSPI https://www.esp32.com/viewtopic.php?t=19233
