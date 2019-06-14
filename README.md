# TinyNB
TinyNB is based on ultra-low-power ARM Cortex M4 32-bit MCU, STM32L431, which has 256KB flash, 64KB SRAM, frequency up to 80 MHz. This board is small, its dimension is 40X60 millimeters.

Two kinds of NB-IOT module are used, Quectel BC95-G for Asia/Europe/Latin America/Africa and BC66 for North America due to different frequency bands for each region
•	North America: B4 (1700), B12 (700), B66 (1700), B71 (600), B26 (850)
•	Asia Pacific: B1(2100), B3(1800), B5(850), B8(900), B18(850), B20(800), B26(850)
and B28(700);
•	Europe: B3 (1800), B8 (900) and B20 (800);
•	Latin America: B2(1900), B3(1800), B5(850) and B28(700)
•	Sub-Saharan Africa: B3(1800) and B8(900);
•	Middle East and North Africa: B8(900) and B20(800);

GPS is included in TinyNB. Quectel L80-R GPS module with an embedded patch antenna (15mm × 15mm × 4mm) and LNA brings high performance of MTK positioning engine to the industrial applications. It is able to achieve the industry’s highest level of sensitivity, accuracy and TTFF with the lowest power consumption in a small-footprint lead-free package. With 66 search channels and 22 simultaneous tracking channels, it acquires and tracks satellites in the shortest time even at indoor signal level.

One temperature and humidity sensor is also on the board. AHT10 is quite small volume, 4x5 millimeters. AHT10 is equipped with a newly designed ASIC chip, an improved MEMS semiconductor capacitive humidity sensing element and a standard on-chip temperature sensing element. Its performance has been greatly improved beyond the reliability level of the previous generation of sensors in harsh environment. 

Signal switch matrix is included for easy debugging. UART of NB-IOT module can be connected with STM32 or with USB port and controlled by PC. UART 2 of STM32 is assigned to NB-IOT module and UART 1 can be connected with USB and output debugging information on PC.
TinyNB can be extended. NBBase extend all IO ports, one UART connector, five I2C connectors, two SPI connectors, four keys which you can define your own function, one OLED screen. With these ports, you can attach any sensors or modules to customize the features. It also comes with lithium battery, you can choose 18650 2900mAH, or 800mAH with smaller size. 5V 250mA solar cell is as well inside the package, so you don’t need worry about the power supply.
