Sourse XLSX available for download in repo.

|                       | ESP32                             | ESP32-S2                                     | ESP32-S3                                     | ESP32-C2<br>(ESP8684)         | ESP32-C3                                     | ESP32-C6                                        | ESP32-H2            |
| --------------------- | --------------------------------- | -------------------------------------------- | -------------------------------------------- | ----------------------------- | -------------------------------------------- | ----------------------------------------------- | ------------------- |
| Processor             | Xtensa LX6 x 1/2<br>240MHz        | Xtensa LX7 x 1<br>240MHz                     | Xtensa LX7 x 2<br>240MHz                     | RISC-V x 1<br>120MHz          | RISC-V x 1<br>160MHz                         | RISC-V x 1<br>160MHz                            | RISC-V x 1<br>96MHz |
| CoreMark (max cores)  | 994.26                            | 472.73                                       | 1181.6                                       | 305.42                        | 307.22                                       | 441.32                                          |                     |
| Per MHz               | 4.14                              | 1.97                                         | 4.92                                         | 2.55                          | 2.55                                         | 2.76                                            |                     |
| (U)LP Co-processor    | Yes                               |                                              | Yes (FSM)                                    |                               |                                              | RISC-V x 1<br>20MHz                             |                     |
| ROM                   | 448KB                             | 128KB                                        | 384KB                                        | 576KB                         | 384KB                                        | 320KB                                           | 128KB               |
| L1                    |                                   |                                              |                                              |                               |                                              | 32KB                                            |                     |
| SRAM                  | 520KB                             | 320KB                                        | 512KB                                        | 272KB (16KB Cache)            | 400KB (16KB Cache)                           | 512KB                                           | 320KB               |
| RTC/LP SRAM           | 16KB                              | 16KB                                         | 16KB                                         |                               | 8KB                                          | 16KB                                            | 4KB                 |
| eFuse bits            | 768                               | 1792                                         | 1792                                         | 256                           |                                              |                                                 |                     |
| Flash                 | QSPI                              | QSPI                                         | QSPI                                         |                               | QSPI                                         | QSPI                                            | QSPI                |
| WiFi                  | 802.11 (b/g/n)<br>2.4GHz only     | 802.11 (b/g/n)<br>2.4GHz only<br>20MHz/40MHz | 802.11 (b/g/n)<br>2.4GHz only<br>20MHz/40MHz | 802.11 (b/g/n)<br>2.4GHz only | 802.11 (b/g/n)<br>2.4GHz only<br>20MHz/40MHz | 802.11 (b/g/n/ax)<br>2.4GHz only<br>20MHz/40MHz |                     |
| WiFi Multimedia (WMM) |                                   |                                              | Yes                                          |                               | Yes                                          | Yes                                             |                     |
| Bluetooth             | 4.2/BTLE                          |                                              | 5.0/BTLE/Mesh                                | 5.0/BTLE                      | 5.0/BTLE/Mesh                                | 5.3/BTLE/Mesh                                   | 5.0/BTLE/Mesh       |
| IEEE 802.15.4-2015    |                                   |                                              |                                              |                               |                                              | Yes                                             | Yes                 |
| Thread                |                                   |                                              |                                              |                               |                                              | 1.3                                             | 1.3                 |
| Zigbee                |                                   |                                              |                                              |                               |                                              | 3                                               | 3                   |
| Timer Groups          | 2                                 | 1                                            | 1                                            | 1                             | 1                                            | 1                                               | 1                   |
| GP Timer              | 2 x 64bit                         | 1 x 64bit                                    | 4 x 56bit                                    | 1 x 54bit                     | 2 x 54bit                                    | 2 x 54bit                                       | 2 x 54bit           |
| System                |                                   | 1 x 64bit                                    | 1 x 52bit                                    | 1 x 52bit                     | 1 x 52bit                                    | 1 x 52bit                                       | 1 x 52bit           |
| Watchdog              | 1                                 | 3                                            | 3                                            | 2                             | 3                                            | 3                                               | 3                   |
| Super Watchdog        |                                   | 1                                            |                                              |                               |                                              |                                                 |                     |
| Analog Watchdog       |                                   |                                              |                                              |                               | 1                                            | 1                                               |                     |
| RTC                   | 1                                 |                                              |                                              |                               |                                              |                                                 |                     |
| Watchdog              | 1                                 | 1                                            | 1                                            | 1                             | 1                                            | 1                                               | 1                   |
| DAC                   | 8bit x 2                          | 8bit x 2                                     |                                              |                               |                                              |                                                 |                     |
| ADC                   | SAR/12bit/9ch x 2                 | SAR/12bit/10ch x 2                           | SAR/12bit/10ch x 2                           | SAR/12bit/5ch                 | SAR/12bit/5ch                                | SAR/12bit/7ch                                   | SAR/12bit/5ch       |
| GPIO                  | 34                                | 43                                           | 45                                           | 14                            | 22                                           | 30                                              | 19                  |
| Strapping             | 5                                 | 3                                            | 4                                            | 2                             | 3                                            | 5                                               |                     |
| Input Only            | 6                                 | 1                                            |                                              |                               |                                              |                                                 |                     |
| In package Flash      | 6                                 | 6                                            | 6                                            |                               |                                              | 6                                               |                     |
| Touch                 | 10                                | 14                                           | 14                                           |                               |                                              |                                                 |                     |
| SPI                   | 4 - QSPI                          | 4 - QSPI                                     | 4 - OSPI                                     | 3 - QSPI                      | 3 - QSPI                                     | 1/2 (Flash Only)                                | 3                   |
| I2C                   | 2                                 | 2                                            | 2                                            | 1 (Master Only)               | 1                                            | 1/1 (LP)                                        | 2                   |
| I2S                   | 2                                 | 1                                            | 2                                            |                               | 1                                            | 1                                               | 1                   |
| Temperature           |                                   | 1                                            | 1                                            | 1                             | 1                                            | 1                                               |                     |
| Pulse Counter         | 8 (4)                             | 4 (2)                                        | 1                                            |                               |                                              | 4                                               | 1                   |
| UART                  | 3                                 | 2                                            | 3                                            | 2                             | 2                                            | 2/1(LP)                                         | 2                   |
| TWAI/CAN              | 1                                 | 1                                            | 1                                            |                               | 1                                            | 2                                               | 1                   |
| ETH                   | 1                                 |                                              |                                              |                               |                                              |                                                 |                     |
| RMT/IR                | 8rx/tx                            | 1tx/1rx                                      | 1tx/1rx                                      |                               | 2tx/2rx                                      | 2tx/2rx                                         | 2tx/2rx             |
| PWM                   |                                   |                                              |                                              |                               |                                              |                                                 |                     |
| Motor                 | 2                                 |                                              | 2                                            |                               |                                              | 1                                               | 1                   |
| LED                   | 16ch                              | 8ch                                          | 8ch                                          | 6ch                           | 6ch                                          | 6ch                                             | 6ch                 |
| PARLIO (Parallel IO)  |                                   |                                              |                                              |                               |                                              | 1                                               | 1                   |
| JTAG                  | 1                                 |                                              | USB                                          |                               | 1                                            | 1                                               | 1                   |
| USB                   | 0                                 | 1                                            | 1?                                           |                               | 1                                            | 1                                               | 1                   |
| OTG                   |                                   | 1                                            | 1                                            |                               |                                              |                                                 |                     |
| ICP                   |                                   | Yes                                          | Yes                                          | Yes                           |                                              | Yes                                             |                     |
| DMA                   | Yes                               | Yes                                          | 5x5                                          | 1x1                           | 3x3                                          | 3x3                                             | 3x3                 |
| Secure Boot           | Yes                               | Yes                                          | Yes                                          | Yes                           | Yes                                          | Yes                                             | Yes                 |
| Flash Encryption      | Yes                               | Yes                                          | Yes                                          | Yes                           | Yes                                          | Yes                                             | Yes                 |
| OTP                   | 1024bit                           | 4096bit                                      | 4096bit                                      | 1024bit                       | 4096bit                                      | 4096bit                                         | 4096bit             |
| Customer              | 768bit                            | 1792bit                                      | 1792bit                                      | 256bit                        | 1792bit                                      | 1792bit                                         | 1792bit             |
| Crypto                |                                   |                                              |                                              |                               |                                              |                                                 |                     |
| ECC                   | Yes                               |                                              |                                              | Yes                           |                                              | Yes                                             | Yes                 |
| SHA                   | Yes                               |                                              |                                              | Yes                           | Yes                                          | Yes                                             |                     |
| RSA                   | Yes                               | Yes                                          | Yes                                          |                               | Yes                                          | Yes                                             | Yes                 |
| AES                   | Yes                               | Yes                                          | Yes                                          |                               | Yes                                          | Yes                                             | Yes                 |
| RNG                   | Yes                               | Yes                                          | Yes                                          | Yes                           | Yes                                          | Yes                                             | Yes                 |
| HASH (FIPS PUB 180-4) |                                   | Yes                                          | Yes                                          |                               |                                              | Yes                                             | Yes                 |
| HMAC                  |                                   | Yes                                          | Yes                                          |                               | Yes                                          | Yes                                             | Yes                 |
| Digital Signature     |                                   | Yes                                          | Yes                                          |                               | Yes                                          | Yes                                             | Yes                 |
| TEE                   |                                   |                                              |                                              |                               |                                              | Yes                                             |                     |
| Sleep                 |                                   |                                              |                                              |                               |                                              |                                                 |                     |
| Active                | 95mA - 240MA                      | 63mA - 310mA                                 | 91mA - 340mA                                 | 62mA - 370mA                  | 84mA - 335mA                                 | 71mA - 354mA                                    | 25mA - 148mA        |
| Modem                 | 20mA - 68mA                       | 10.5mA - 28mA                                | 13.2mA - 107.9mA                             | 9.4mA - 15.6mA                | 13mA - 28mA                                  | 14mA - 38mA                                     | 3mA - 17mA          |
| Light                 | 0.8mA                             | 0.75mA                                       | 0.24mA                                       | 0.140mA                       | 0.130mA                                      | 35uA - 0.180mA                                  | 25uA - 85uA         |
| Deep                  | 10uA                              | 20uA - 170uA                                 | 7uA - 8uA                                    | 5uA                           | 5uA                                          | 7uA                                             | 7uA                 |
| Hibernation           | 1uA - 5uA                         | 1uA (Off)                                    | 1uA (Off)                                    | 1uA (Off)                     | 1uA (Off)                                    | 1uA (Off)                                       | 1uA (Off)           |
| Timers                |                                   |                                              |                                              |                               |                                              |                                                 |                     |
| Internal              | 8MHz                              | Requires External                            | Requires External                            | Requires External             | Requires External                            | Requires External                               | Requires External   |
| Internal RC           | Yes                               | Requires External                            | Requires External                            | Requires External             | Requires External                            | Requires External                               | Requires External   |
| External              | 2MHz - 60MHz<br>(WiFi/BT - 40MHz) | n - 240MHz                                   | n - 240MHz                                   | n - 120MHz                    | n - 160MHz                                   | n - 160MHz                                      | n - 96MHz           |
| External RTC          | 32kHz                             |                                              |                                              |                               |                                              |                                                 |                     |
| XTAL32K watchdog      |                                   | 1                                            |                                              |                               |                                              |                                                 |                     |
| Host                  |                                   |                                              |                                              |                               |                                              |                                                 |                     |
| SD                    | 1 (Shared)                        |                                              | 1 (2 Slots)                                  |                               |                                              |                                                 |                     |
| eMMC                  | 1 (Shared)                        |                                              | 1 (2 Slots)                                  |                               |                                              |                                                 |                     |
| SDIO                  | 1 (Shared)                        |                                              |                                              |                               |                                              |                                                 |                     |
| Slave                 |                                   |                                              |                                              |                               |                                              |                                                 |                     |
| SPI                   | 1 (Shared)                        |                                              |                                              |                               |                                              |                                                 |                     |
| SDIO                  | 1 (Shared)                        |                                              |                                              |                               |                                              | 1                                               |                     |
| Camera                |                                   |                                              |                                              |                               |                                              |                                                 |                     |
| DVP (I2S)             |                                   | 1                                            | 1? I2S                                       |                               |                                              |                                                 |                     |
| LCD                   |                                   |                                              |                                              |                               |                                              |                                                 |                     |
| Serial                |                                   | 1 (SPI2)                                     | 1?                                           |                               |                                              |                                                 |                     |
| Parallel              |                                   | 1 (I2S)                                      |                                              |                               |                                              |                                                 |                     |
