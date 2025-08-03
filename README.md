# Real-Time Acquisition of Environmental Parameters and Weather Prediction using MSP430

This project demonstrates the **real-time acquisition of environmental parameters** using embedded sensors and subsequent **weather condition prediction** using machine learning. The system is built around the **MSP430 microcontroller**, offering a low-power, portable, and scalable solution for on-site weather sensing and forecasting.

## Key Features

- **Sensor-Based Data Acquisition:**
  - Captures **temperature**, **humidity**, and **ambient light intensity** using high-precision digital sensors.
  - Real-time sampling with noise filtering and adaptive calibration.
  
- **Embedded System Design:**
  - Built on **TI MSP430**, optimized for low power consumption and fast wake-up cycles.
  - Efficient use of peripherals for I²C/SPI sensor interfacing, UART logging, and LCD display.

- **Data Calibration and API Validation:**
  - Sensor readings are cross-referenced with real-time data from the **Tomorrow.io Weather API** for enhanced accuracy.
  - Ensures consistency in harsh or changing environments.

- **On-Device Weather Forecasting:**
  - A trained **feedforward neural network** (3-layer, ReLU activations) predicts weather states (sunny, cloudy, humid, rainy).
  - Achieved an overall **forecasting accuracy of ~96%** in varied real-world testing conditions.

- **User Feedback and Display:**
  - Outputs sensor values and predicted weather state on an **LCD interface**.
  - UART interface for data logging or cloud sync support.

## Applications

- Smart farming and irrigation systems  
- Localized weather stations for urban planning  
- Educational platforms for embedded AI  
- Industrial automation based on weather sensitivity  

## Possible Future Improvements

- Support for additional sensors (barometric pressure, wind speed, air quality)  
- Integration with GSM or LoRaWAN for remote deployments  
- Deep learning models (LSTM/GRU) for extended forecasting  
- Solar-powered version for off-grid locations  

This project effectively bridges the gap between **sensor-driven environmental monitoring** and **on-device intelligent weather prediction**, showcasing the synergy between embedded systems and AI in a power-constrained setup.
