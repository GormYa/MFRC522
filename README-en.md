# MFRC522
This application reads the serial number of Mifare cards using MFRC522-powered readers/writers. It's intended for Raspberry Pi 3.

## How to connect the reader to the Raspberry Pi

Connect your reader according to the table, leave the IRQ pin unconnected

MFRC522 | Physical pin | BCM number
------- | ------------ | ----------
SDA     | 24           | 8
SCK     | 23           | 11
MOSI    | 19           | 10
MISO    | 21           | 9
IRQ     | ---          | ---
GND     | 6*           | ---
RST     | 22           | 25
3.3V    | 1 or 17      | ---

\*Alternative pins (physical): 9,14,20,25,30,34,39
