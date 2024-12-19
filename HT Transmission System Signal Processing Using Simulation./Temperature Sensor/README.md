The LM35 temperature sensor is a 3-pin analog sensor widely used for temperature measurement. When integrated with platforms like Raspberry Pi, it provides precise digital temperature readings. The Raspberry Pi processes signals from the LM35 using techniques such as noise filtering, signal amplification, and analog-to-digital conversion (ADC), making it suitable for applications like environmental control and industrial systems.

STEPS FOR SIMULATION IN PROTEUS:

SIMULATE LM35 OUTPUT : Add a variable voltage source in Proteus to simulate the varying output voltage of the LM35 temperature sensor, reflecting changes corresponding to simulated temperature variations.

INTEGRATE MICROPROCESSOR : Include a Raspberry Pi model in the Proteus simulation to serve as the intermediary device for processing the simulated sensor output.

ESTABLISH ADC CONNECTION : Connect the LM35's output to the Analog-to-Digital Converter (ADC) input pin of the Raspberry Pi, enabling the transmission of analog data for further processing.

PROGRAM THE RASPBERRY PI : 

1.Write Python code to read the analog voltage signal received from the LM35 temperature sensor, interfaced with the Raspberry Pi's ADC pin.

2.Utilize the Raspberry Pi's built-in ADC functionality to convert the analog voltage signal into a corresponding digital value.

INTERPRET DIGITAL DATA : The ADC conversion process enables the microprocessor to interpret temperature data in a digital format, facilitating subsequent analysis and utilization within the simulated environment.

KEY CALCULATIONS:

I. TEMPERATURE CONVERSION :

Equation : T (Celsius) = (Vsensor - Voffset) / Sensitivity + Toffset

Where:

T: Temperature in Celsius

Vsensor: Voltage output from the temperature sensor

Voffset: Optional offset voltage

Sensitivity: Sensor's sensitivity (typically 10 mV/°C for LM35)

Toffset: Optional temperature offset

II. ADC CONVERSION :

Equation: Digital Value = (Analog Voltage - ADC Offset) / ADC Resolution

Where:

Analog Voltage: Voltage from the sensor

ADC Offset: Offset voltage of the ADC (if any)

ADC Resolution: Number of bits in the ADC (e.g., 10-bit, 12-bit)

III. VOLTAGE REGULATION :

Equation: Vout = Vin * (R2 / (R1 + R2))

Where:

Vout: Regulated output voltage

Vin: Input voltage

R1, R2: Resistances in the voltage divider circuit

![LM35](https://github.com/user-attachments/assets/77ee5716-5918-4a39-9959-e8ab45104754)


