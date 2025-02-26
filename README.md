# lora-starter-edition-sx1262-i2c
Raspberry Pi Starter Edition HAT (i2c breakout and single spi core1262 only)

SX1262 with TXCO
I2C pins groove pinout

![image](https://github.com/user-attachments/assets/6c572e8a-0aeb-484d-b47b-389315f6ab72)

Currently Tested on

BPI-R4
Raspberry PI 3A

Next
ESP32 One
RP2040-Pi-Zero
Milk-v DUO/DUO256
Milk-v DUOS

BananaPi-BPI-R4-sx1262.yaml
```
Lora:
  Module: sx1262  # BananaPi-BPI-R4 SPI via 26p GPIO Header
##  CS: 28
  IRQ: 50
  Busy: 62
  Reset: 51
  spidev: spidev1.0
  DIO2_AS_RF_SWITCH: true
  DIO3_TCXO_VOLTAGE: true
```

lora-starter-edition-sx1262-i2c.yaml
```
# https://www.waveshare.com/core1262-868m.htm
Lora:
  Module: sx1262  # Starter Edition SX1262 I2C Raspberry Pi HAT
  DIO2_AS_RF_SWITCH: true
  DIO3_TCXO_VOLTAGE: true
  CS: 8
  IRQ: 22
  Busy: 4
  Reset: 18
```
