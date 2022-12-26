# arduino-esp32-SOLO

从淘宝老王家淘了不少拆机的单核ESP32模块,更新一下Arduino的单核ESP32编译环境

## UPDATE 2022.12.27
* Update to ESP32 2.0.6
* Success compiler in ArduinoIDE 2.0.3 and old Arduino 1.8.19
* modify sdkconfig, add
<code>
CONFIG_FREERTOS_UNICORE=y
</code>
for ESP32 single core

These libraries allow you to compile arduino-esp32 applications for the ESP32-SOLO single core MCU.  Just replace the files in your esp32 directory with the included files.
The libraries are only compiled for release versions of arduino-esp32.  Checkout the commit corresponding to your version in Arduino IDE boards manager.
