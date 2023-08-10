# Indoor-Air-Quality-Monitoring

I used a microcontroller and gas sensors along with temperature and humidity sensors that will monitor indoor air quality. The microcontroller I used is ESP32. The gas sensors are MQ135 for the detection of carbon monoxide, benzene, ammonia, and alcohol; MQ5 for the detection of natural gas, LPG; MQ2 for methane, butane, and smoke. The DHT11 sensor is used to get the temperature and humidity. Based on the values collected from sensors the microcontroller will decide the air quality based on previously hard-coded thresholds. I used a 16x2 LCD display and a series of LEDs to visualize  the results and display the AQI, temperature, humidity, and alert messages along with indications in LEDS.

Board: DOIT ESP32 DEVKIT V1
Language: Arduino Programming Language (Framework built on top of C++)
Sensors: MQ135 (Gas Sensor), DHT11 (Humidity and Temperature)
Other components: LEDs, Buzzer and LCD Display
