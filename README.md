# MFRC522
Bu uygulama, MFRC522 destekli okuyucular/yazıcılar kullanarak Mifare kartlarının seri numarasını okur. Raspberry Pi 3 için tasarlanmıştır.

## Okuyucu Raspberry Pi'ye nasıl bağlanır?

Okuyucunuzu tabloya göre bağlayın, IRQ pinini bağlantısız bırakın.

MFRC522 | Fiziksel pin | BCM numarasi
------- | ------------ | ----------
SDA     | 24           | 8
SCK     | 23           | 11
MOSI    | 19           | 10
MISO    | 21           | 9
IRQ     | ---          | ---
GND     | 6*           | ---
RST     | 22           | 25
3.3V    | 1 veya 17    | ---

\*Alternatif pinler (fiziksel): 9, 14, 20, 25, 30, 34 ve 39.
