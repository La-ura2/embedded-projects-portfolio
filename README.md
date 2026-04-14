# embedded-projects-portfolio

## 1. Voltage Measurement Circuit (LM741/LM358)
- **Tools:** LTspice
- **Description:** Designed and simulated an inverting amplifier configuration to measure 0-5V input with 0-3.3V output (for ADC interfacing)
- **Files:** `LTspice_schematic.asc`, simulation results below
- **Key learning:** Op-amp gain calculation, frequency response analysis



## 2. STM32F407 I2C Accelerometer Integration
- **Microcontroller:** STM32F407G-DISC1
- **Sensor:** MPU6050 (accelerometer + gyroscope)
- **Protocol:** I2C (SDA on PB7, SCL on PB6)
- **Features:** 
  - Initialized I2C at 100kHz
  - Read accelerometer raw data (X, Y, Z axes)
  - Converted to g-force values
- **Files:** `main.c`, `i2c_config.c`, `accelerometer_driver.h`


