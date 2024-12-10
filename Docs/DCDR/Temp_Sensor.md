[Overview](./Dev_Board.md)

# Temp Sensor
The temperature sensor used is the **MCP9700T-E/LT**. It has a single analog output that ranges from +20C to +70C with a 10 mV/C resolution.

# Schematic
![Temp Sensor Schematic](../Assets/Temp_Sensor/Temp_Sensor_Schematic.png)

# Component Pinout
![Temp Sensor Pinout](../Assets/Temp_Sensor/Temp_Sensor_Pinout.png)

# Peripheral Components
## 1 uF Capacitor
![1 uF Capacitor](../Assets/1uF_Cap/1uF_Cap_Specs.png)

## 200 Ohm Resistor
![200 Ohm Resistor](../Assets/200Ohm_Res/200Ohm_Res_Specs.png)

# Simulation
The lowpass filter used for the temperature sensor has a cutoff frequency of around 800 Hz.

![Cutoff Frequency Calculations](../Assets/Temp_Sensor/Temp_Sensor_Cutoff_Calculations.png)

This filter was then simulated.

![Filter Circuit Simulated Schematic](../Assets/Temp_Sensor/Temp_Sensor_Simulated_Circuit.png)

![Filter Circuit Simulation Results](../Assets/Temp_Sensor/Temp_Sensor_Simulation_Results.png)
