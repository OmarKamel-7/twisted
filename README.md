# Twisted
Twisted is a tiny (14x32mm to be precise) ESP32-S3 based platform, which has dual Xtensa LX7 cores, 4Mb of flash, 2Mb of PSRAM, 512Kb of SRAM as well as BLE and WiFi on board, paired with an [0.42" IPS LCD](https://www.buydisplay.com/0-42-inch-mini-color-tft-lcd-display-module-96x54-ips-st7735), a keypad, a Neopixel and built-in battery management with USB OTG.

<img width="506" height="1003" alt="pcb layer by layer view" src="https://github.com/user-attachments/assets/31b31c68-d2c5-4c42-9ac7-b3aa04d9d765" />

There is one more thing, the platform is extendable! It features a 20pin 1.27mm expansion header which allows you of attaching other boards that add more feature, and also give the _Twisted_ a reason for its name.

We currently have two expansion boards for Twisted...
- **Twisted Listen**: An audio codec based on ES8316, which provides a high performance DAC and ADC, the attachment comes with both a builtin microphone and amplifier for a loudspeaker, as well as a 3.5mm headphone jack (with microphone in.)
- **Twisted Sense**: An attachment that provides a a suite of sensors and trackers (pressure, temperature, humidity, gyroscope, accelerometer, magnetometer and GPS/GNSS) aiming to help the device "feel" what happens surround it.
