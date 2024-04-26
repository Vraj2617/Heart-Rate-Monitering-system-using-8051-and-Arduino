# Heart Rate Monitoring System using 8051 Microcontroller
This project is a Heart Rate Monitoring System implemented using an 8051 microcontroller. The system utilizes an Arduino as an analog-to-digital converter (ADC) to read data from a pulse sensor and pass it to the 8051 microcontroller. The microcontroller then displays the heart rate data on an LCD screen. Additionally, the system includes three modes: Relax mode for BPM less than 80, Active mode for BPM between 80 to 120, and Alert mode for BPM greater than 120.

## Components Used:
- 8051 Microcontroller
- Arduino
- Pulse Sensor
- LCD Display

## Features:
- Measures heart rate using a pulse sensor.
- Displays heart rate data on an LCD screen.
- Three modes: Relax, Active, and Alert, based on heart rate range.

## Procedure:
- Connect the pulse sensor to the Arduino and the Arduino to the 8051 microcontroller.
- Upload the Arduino code to read analog data from the pulse sensor and transmit it to the 8051 microcontroller.
- Upload the 8051 microcontroller code to receive data from the Arduino and display it on the LCD screen.
- Power on the system and place the pulse sensor on the subject's fingertip.
- The LCD will display the current heart rate and the corresponding mode.

## Modes:
- Relax Mode: Heart rate below 80 BPM.
- Active Mode: Heart rate between 80 to 120 BPM.
- Alert Mode: Heart rate above 120 BPM.

## Connections:
- **Pulse Sensor to Arduino:**
Connect Pulse Sensor's analog output (A0) to Arduino's analog pin A0.
Provide 5V and GND from Arduino to the Pulse Sensor.
- **Arduino to 8051 Microcontroller:**
Connect Arduino's TX pin to 8051's RX pin.
Connect Arduino's RX pin to 8051's TX pin.
- **8051 Microcontroller to LCD:**
Connect the data pins of the LCD to Port 1 of the 8051 microcontroller.
Connect RS, RW, and EN pins of the LCD to P2.0, P2.1, and P2.3 of the 8051 microcontroller, respectively.


