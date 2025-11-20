# Arduino Water Sensor Alarm

This project uses a water sensor connected to an Arduino UNO to detect moisture.
If the sensor value is above a threshold, the LED and buzzer are activated.

## Wiring
- Sensor VCC → Arduino 5V
- Sensor GND → Arduino GND
- Sensor SIG → Arduino A0
- LED → Pin 13
- Buzzer → Pin 12

## Code
See `water_sensor_alarm.ino` for the full sketch.
