# RTU-Rocket-Telemetry-Unit-
The RTU(Rocket Telemetry Unit) is an all-in-one solution for logging and transmitting data, plus controlling up to 3 servos. 

## Specifications
The RTU contains the following:<br>
MCU: STM32H725RGV6<br>
Barometer: BMP581<br>
IMU: BMI270<br>

For Power, the RTU has a 3.3V regulator and a 5v regulator for servos. 
<img width="622" height="562" alt="Screenshot 2026-10-31 203006" src="https://github.com/user-attachments/assets/9d1d6aff-2246-49c5-a48b-c4fc78c4c1ea" />

## Recording Data
The RTU can record data to an SD card, provided that an SD card is inserted into the SD card port.  
<img width="593" height="499" alt="Screenshot 2026-10-31 185222" src="https://github.com/user-attachments/assets/c8eeb2c1-8105-42be-a6bc-1222d0874c60" />
## Transmitting Data
The RTU can transmit data through an on-board LoRa module; you must connect the appropriate u.fl antenna to the antenna port for the module to transmit. 
<img width="703" height="569" alt="Screenshot 2026-10-31 202229" src="https://github.com/user-attachments/assets/c73f6aae-0719-4480-92d0-f24bea467e1c" />
## Servo Control
The RTU can control up to three 5V servos; the servo ports can be found in these locations:
<img width="644" height="589" alt="Screenshot 2026-10-31 202509" src="https://github.com/user-attachments/assets/f238ee2a-e590-41ba-a623-f5fd7fa4d06b" />

# Important Information
To ensure that the 3.3V regulator works correctly, make sure to place only ONE of the resistors circled; it is recommended to place the FPWM resistor and not the PWM resistor.
<img width="477" height="330" alt="Screenshot 2026-10-31 203311" src="https://github.com/user-attachments/assets/677395f6-11e5-44e8-8ef5-ad82d745b5c8" />
