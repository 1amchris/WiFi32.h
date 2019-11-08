# Quick fix for "multiple WiFi libraries" issue on Arduino IDE
#include &lt;WiFi32.h> instead of #include &lt;WiFi.h> as it collides with the built-in arduino library

# How to install ?
Simply download the git repo and drag-n-drop the "Wifi32.h" in the "\[arduinoFolder]\packages\esp32\hardware\esp32\1.0.X\libraries\WiFi\src\"

# How to use ?
You will be able to use the ESP32 WiFi.h library explicitly by including <WiFi32.h> instead of <Wifi.h>
