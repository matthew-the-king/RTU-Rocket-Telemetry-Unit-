# RTU-Rocket-Telemetry-Unit-
The RTU(Rocket Telemetry Unit) is an all-in-one solution for logging and transmitting data, plus controlling up to 3 servos. 

## Specifications
The RTU contains the following:<br>
MCU: STM32H725RGV6<br>
Barometer: BMP581<br>
IMU: BMI270<br>

For Power, the RTU has a 3.3V regulator and a 5v regulator for servos.<br>
<img width="622" height="562" alt="Screenshot 2026-10-31 203006" src="https://github.com/user-attachments/assets/9d1d6aff-2246-49c5-a48b-c4fc78c4c1ea" />

## Recording Data
The RTU can record data to an SD card, provided that an SD card is inserted into the SD card port.<br>
<img width="593" height="499" alt="Screenshot 2026-10-31 185222" src="https://github.com/user-attachments/assets/c8eeb2c1-8105-42be-a6bc-1222d0874c60" />
## Transmitting Data
The RTU can transmit data through an on-board LoRa module; you must connect the appropriate u.fl antenna to the antenna port for the module to transmit.<br>
<img width="703" height="569" alt="Screenshot 2026-10-31 202229" src="https://github.com/user-attachments/assets/c73f6aae-0719-4480-92d0-f24bea467e1c" />
## Servo Control
The RTU can control up to three 5V servos; the servo ports can be found in these locations:<br>
<img width="644" height="589" alt="Screenshot 2026-10-31 202509" src="https://github.com/user-attachments/assets/f238ee2a-e590-41ba-a623-f5fd7fa4d06b" />

## Production 
|Designator                                                                                      |Footprint                               |Quantity|Value                  |LCSC Part #|
|------------------------------------------------------------------------------------------------|----------------------------------------|--------|-----------------------|-----------|
|C10, C12, C19, C28, C36, C40                                                                    |0603                                    |6       |1uF                    |           |
|C11, C29, C30, C37, C38, C39                                                                    |0603                                    |6       |10uF                   |           |
|C13, C14, C15, C16, C17, C18, C21, C22, C27, C3, C32, C34, C35, C4, C42, C43, C5, C6, C7, C8, C9|0402                                    |21      |0.1uF                  |           |
|C2, C49, C50                                                                                    |0603                                    |3       |22uF                   |           |
|C20, C31, C41, C46, C47, C48                                                                    |CAP_E61_CHC                             |6       |100uF                  |           |
|C23, C24                                                                                        |0603                                    |2       |2.2uF                  |           |
|C25, C26                                                                                        |0402                                    |2       |10pF                   |           |
|C33                                                                                             |0603                                    |1       |4.7uF                  |           |
|C44                                                                                             |0603                                    |1       |4700pF                 |           |
|C45                                                                                             |0402                                    |1       |100pF                  |           |
|D1                                                                                              |0805                                    |1       |LED                    |           |
|FB1                                                                                             |0603                                    |1       |120R                   |           |
|FPWM1, PFM1, R15, R16, R6, R7                                                                   |0402                                    |6       |10kΩ                   |           |
|J1                                                                                              |GCT_MEM2075-00-140-01-A                 |1       |MEM2075-00-140-01-A    |           |
|J10                                                                                             |PinHeader_1x02_P2.54mm_Vertical         |1       |5V_Rail                |           |
|J2                                                                                              |SAMESKY_UJ20-C-H-G-SMT-P16-TR           |1       |UJ20-C-H-G-SMT-1-P16-TR|           |
|J3                                                                                              |PinHeader_1x06_P2.54mm_Vertical         |1       |Debug                  |           |
|J4                                                                                              |JST_B6B-XH-A                            |1       |B6B-XH-A               |           |
|J5                                                                                              |JST_B4B-XH-A                            |1       |B4B-XH-A               |           |
|J6, J7, J8                                                                                      |PinHeader_1x03_P2.54mm_Vertical         |3       |Servo                  |           |
|J9                                                                                              |PinHeader_1x02_P2.54mm_Vertical         |1       |Power                  |           |
|L1                                                                                              |1008                                    |1       |1uH                    |           |
|L2                                                                                              |L_Wurth_WE-LHCA-1040                    |1       |4.7uH                  |           |
|R1, R2                                                                                          |0402                                    |2       |5.1kΩ                  |           |
|R10                                                                                             |0402                                    |1       |330Ω                   |           |
|R11, R12, R4, R5                                                                                |0402                                    |4       |4.7kΩ                  |           |
|R13                                                                                             |0402                                    |1       |27.4kΩ                 |           |
|R14                                                                                             |0402                                    |1       |23.2kΩ                 |           |
|R3                                                                                              |0402                                    |1       |0Ω                     |           |
|R8                                                                                              |0603                                    |1       |511kΩ                  |           |
|R9                                                                                              |0603                                    |1       |91kΩ                   |           |
|U1                                                                                              |QFN-68-1EP_8x8mm_P0.4mm_EP6.4x6.4mm     |1       |STM32H725RGVx          |           |
|U2                                                                                              |QFN10_BMP581_BOS                        |1       |BMP581                 |           |
|U3                                                                                              |XDCR_BMI270                             |1       |BMI270                 |           |
|U4                                                                                              |COMM-SMD_12P-L11.6-W11.0-P1.27_114993390|1       |WIO-SX1262_C9900174795 |C9900174795|
|U5                                                                                              |PSON50P145X100X60-6N                    |1       |TPD4S012DRYR           |           |
|U6                                                                                              |VAL0015A-MFG                            |1       |XTPS55285VALR          |           |
|U7                                                                                              |SOT50P160X60-8N                         |1       |TPS631000DRLR          |           |
|Y1                                                                                              |CRYSTAL_ABM8G_ABR                       |1       |ABM8G-25.000MHZ-B4Y-T  |           |


## Firmware
currently no firmware because I do not have the board yet.

# Important Information
To ensure that the 3.3V regulator works correctly, make sure to place only ONE of the resistors circled; it is recommended to place the FPWM resistor and not the PFM resistor.<br>
<img width="477" height="330" alt="Screenshot 2026-10-31 203311" src="https://github.com/user-attachments/assets/677395f6-11e5-44e8-8ef5-ad82d745b5c8" />
