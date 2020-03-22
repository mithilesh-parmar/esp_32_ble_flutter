# esp_connect

A Flutter application to communicate with esp32 using ble.

## Getting Started


# ESP-32
1. Create a new project and copy the code from file /esp_32/ble.ino
2. From Board manager select Esp32 Dev Board
3. upload the code to esp32


# FLUTTER APP
1. For Mobile Device to detect BLE Devices nearby make sure to start bluetooth and location services before starting the app
2. Run the project on physical device
3. Open Setting page on the app and look for ESP32 bluetooth device (If it doesn't show press back and open the setting page again repeat 2-3 times, make sure to be in close vicinity with esp32)
4. Restart the Esp and app if above step fails.
5. Click on it to connect
6. change the switch to Switch on or off the builtin led