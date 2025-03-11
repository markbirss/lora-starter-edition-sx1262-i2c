# Raspberry Pi Starter Edition HAT with TXCO

Raspberry Pi Starter Edition HAT (i2c breakout and single spi core1262 only)

SX1262 with TXCO

I2C pins groove pinout


![337162122407936-Produce_DanZhi SMT_Snapshot Top 3441618A_Y41 SMT025021360898 (1)](https://github.com/user-attachments/assets/db96b5ef-8181-4f72-9fa0-d28cf9fad821)

![image](https://github.com/user-attachments/assets/6c572e8a-0aeb-484d-b47b-389315f6ab72)

Currently Tested on

BPI-R4

Raspberry PI 3A

ESP32 One

RP2040-Pi-Zero

Raxda Rock 2F


Next

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

# **JLBPCB Gerber view (online**
https://jlcpcb.com/RGE

# **DISCLAIMER**

# Use of these GERBER, BOM and CPL are at your own risk

Support my work and considder **buying  me a coffee**

https://buymeacoffee.com/mark.birss
