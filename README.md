# Jukebox

An ESP32 based jukebox driven by ESPHome and Home Assistant.

---

About the project: it’s a simple ESP32 based media player that allows scanning cards with RFID tags to select the media to play. Everything will be tight together with ESPHome (for the ESP32 firmware side) and Home Assistant.

It’s a simple 2-layer board with 1.6mm thickness and 4cm x 6cm overall size.

The board features the following main parts:

- ESP32-WROOM-32E as the MCU
- AMS1117-3.3 as a power regulator
- CH340C as the serial converter
- MAX98357AETE+T as a DAC with integrated 3w amp
- connectors for three simple buttons (volume -/+, play/pause)
- connector for an PN532 based RFID module connected via I2C
- connector for a passive broadband speaker
