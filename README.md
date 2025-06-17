# Annunciation-System-for-central-plant

**Overview**

The goal of this project is to create a central plant temperature monitoring system without the need for a microcontroller.  It continuously compares the real-time result from a temperature sensor with the threshold temperature that the user sets with a potentiometer.  The system sounds a buzzer and turns on an LED as warning signals if the sensor finds a temperature that is greater than the predetermined point.  There is no notice if the temperature stays below the threshold.

**Features**

Analog Threshold Setting using potentiometer
Real-Time Temperature Comparison
Buzzer & LED Alert when temperature exceeds limit
No Microcontroller Used – implemented using analog components
Custom Circuit Design created from scratch

**Components Used**

Temperature Sensor (e.g., LM35)
Potentiometer
Operational Amplifier (Comparator configuration)
Buzzer
LED
Power Supply
Discrete components (resistors, transistors, etc.)

**Working Principle**

A reference voltage equal to the intended threshold temperature is established via the potentiometer.
A voltage corresponding to the actual temperature is output by the temperature sensor.
These voltages are compared in a comparator circuit.
The buzzer and LED are activated if the sensor voltage surpasses the reference.
If below, there is no notice and the circuit is left inactive.

**Applications**

Industrial plant temperature monitoring
Boiler and HVAC systems
Safety alert systems without programmable logic

