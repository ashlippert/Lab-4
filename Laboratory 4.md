# Lab 4: Go Big - Operational Amplifiers

**Authors:**

Ashlyn Lippert and Seth Daniel

**Date:**

February 24th, 2025

## Introduction
   The purpose of this lab is to learn how to use operational amplifiers (Op Amps) to construct basic amplifier and signal conditioning circuits and to discover the performance limitations of the devices. In these exercises we built inverting amplifying circuits, low, moderate, and high-gain circuits, a voltage follower, and integrating and differentiating circuits. Once constructed, we will measure important characteristics of the circuits and observe the signals using an oscilloscope.

## Materials
1. Resistors: 1 kΩ, 4.7 kΩ, 8.2 kΩ, 22 kΩ, two 68kΩ, 220 kΩ, 330 kΩ, and 1.5 MΩ
2. 2 DC Power Supplies (DCPS)
3. Fluke 87 V DMM
4. LM741 Op Amp
5. Additional wires
6. Oscilloscope
7. Capacitors: 1 nF, 100 nF
8. A 10 kΩ trimmer potentiometer
9. Flathead screwdriver
10. Breadboard
11. Function Generator

## Assembly Methods

**Assembling the Power Supply**
   The following lab utilizes two DC Power Supplies (DCPS) where the positive output of one is connected to the ground. The dual DCPS setup used for this lab can be described by Figure 1 below.

<div align= "center">
<img src="https://github.com/user-attachments/assets/6f79af6e-2f60-4537-8b5c-78980a8795f3" alt "Schematic 1" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 1: Setup of 2 DCPS. </figcaption>
</div>

**Objective 1: Limits of Op Amps**

1.1. **Unity Gain Inverting Op Amp Circuit**

   The unity gain inverting op amp circuit was constructed according to the schematic shown in Figure 2. The voltage divider was connected to the positive and negative voltage supplies. The 10 kΩ potentiometer was adjusted using a flat head screwdriver to change the input voltage.

<div align= "center">
<img src="https://github.com/user-attachments/assets/f3d6dfed-6490-4f5b-a008-85dc8d73c400" alt "Schematic 1" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 2: Schematic describing the unity gain inverting op amp circuit built for part 1 of this lab. </figcaption>
</div>

<br>

   Once assembled, the circuit created using schematic 1 should resemble what is shown in Figure 3 below.
<div align= "center">
<img src="https://github.com/user-attachments/assets/2b5ec215-5c07-42e6-8ee8-ea23271a593c" alt "Circuit 1" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 3: Constructed unity gain inverting op amp circuit from Schematic 1. </figcaption>
</div>
<br>

1.2. **Moderate Gain Inverting Op Amp Circuit**

   The moderate gain inverting op amp circuit was assembled following the schematic shown in Figure 4. The function generator was set to 100mV and 2 kHz and connected to Vi, as shown in Figure 5. 


<div align="center">
<img src="https://github.com/user-attachments/assets/6a652a9d-c4e2-461c-9e93-3904b0991b73" alt="Schematic 2" width="400"/>
   
<br/>
   
  <figcaption style="font-size: 16px; text-align: center;"> Figure 4: Schematic 2, moderate gain inverting op amp circuit. </figcaption>
</div>

<br>

   When constructed, the circuit assembled using Schematic 2 should resemble Figure 4. For this constructed circuit, a 68 kΩ resistor was placed in front of the Function Generator.

   <div align="center">
  <img src="https://github.com/user-attachments/assets/e5545ff6-a57e-4884-9d19-4f66c70b305a" alt="Circuit 2" width="400"/>
      
<br>
   
  <figcaption style="font-size: 16px; text-align: center;"> Figure 5: Constructed circuit from Schematic 2. </figcaption>
</div>   


<br>

1.3. **High-Gain Inverting Op Amp Circuit**

   The high-gain inverting op amp circuit was built according to the schematic given in Figure 5. Additionally, the function generator was set to 10mV and 2 kHz.

<div align="center">
<img src="https://github.com/user-attachments/assets/37adea5c-f6c2-471a-aeec-44187eb0d36e" alt="Schematic 3" width="400"/>
<br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 6: High gain inverting op amp schematic. </figcaption>

   Unfortunately, our group did not take a photo of the constructed circuit for Schematic 3, but when constructed, the circuit assembled using Schematic 3 should have the same setup as the previous circuit in Figure 5, but with resistors values of 1.5 MΩ and 1 kΩ. For this constructed circuit, a 68 kΩ resistor was also placed in front of the Function Generator.
<br>
</div>

**Objective 2: Op Amps and Frequency Response**


2.1. **Voltage Follower Circuit**

   The voltage follower circuit was constructed following the given schematic. The function generator was set to 1V amplitude and 2 kHz frequency, and it was connected to Vi.

<div align="center">
<img src="https://github.com/user-attachments/assets/05193f3f-e39c-44ee-b2ad-e1f052b6da63" alt="Schematic 4" width="400">
<br/>

<figcaption style="font-size: 16px; text-align: center;"> Figure 7: Voltage follower op amp circuit schematic. </figcaption>
</div>   

<br/>
  Once assembled, the circuit should look resemble Figure 8 below.

   <div align="center">
  <img src="https://github.com/user-attachments/assets/1e3d7d5b-bb39-4b12-9abe-971e10933cd9" alt="Assembled voltage follower op amp circuit" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 8: Constructed voltage follower op amp circuit from Figure 7. </figcaption>
</div>
<br>

2.2. **Integrating Op Amp Circuit**

   The integrating op amp circuit was assembled according to the schematic given in Figure 9. The function generator was connected to Vi.

<div align="center">
<img src="https://github.com/user-attachments/assets/4efbc658-43d3-44e1-a12a-e7e4daccd3dd" alt="Schematic 5" width="400">
<br/>

<figcaption style="font-size: 16px; text-align: center;"> Figure 9: Integrating op amp schematic. </figcaption>
</div>   

<br/>
  Once assembled, the circuit should look resemble Figure 10 below.

   <div align="center">
  <img src="https://github.com/user-attachments/assets/262fddca-2d42-4608-9ca7-bd8a3384331c" alt="Assembled Integrating op amp circuit" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 10: Constructed intergrating op amp circuit. </figcaption>
</div>

<br>

2.3. **Differentiating Op Amp Circuit**
   The differentiating op amp circuit was built following the schematic shown in Figure 11. The function generator was connected to Vi for this circuit.


<div align="center">
<img src="https://github.com/user-attachments/assets/dda2b54f-a855-4d3c-8e59-73c12867e2c4" alt="Schematic 6" width="400">
<br/>

<figcaption style="font-size: 16px; text-align: center;"> Figure 11: Differentiating op amp schematic. </figcaption>
</div>   

<br/>
  Once assembled, the circuit should look resemble Figure 8 below.

   <div align="center">
  <img src="https://github.com/user-attachments/assets/78e4e640-8950-4402-a60b-a432eed23603" alt="Assembled differentiating op amp circuit" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 12: Constructed differentiating op amp schematic. </figcaption>
</div>
<br>

## Test Equipment

1. Fluke 87 V DMM
2. DC Power Supply
3. Oscilloscope
4. Function Generator
   
## Test Procedures

**Resistor Measurement**

   For this part of the experiment, the resistance each resistor was measured using a Digital Multimeter (DMM) and the results were compared to the expected values based on the resistor color codes. We recorded the expected resistance, the acceptable tolerance range, and the measured resistance in a table. Any resistors that fell outside the expected range were noted. The technique used for resistor measurement is shown in Figure 13 below.

 <div align="center">
  <img src="https://github.com/user-attachments/assets/fd70fd10-4528-41e1-9a64-bf901897e7e4" alt="Assembled differentiating op amp circuit" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 13: Measuring Resistor Values. </figcaption>
</div>
<br>


**Part 1.1: Unity Gain Inverting Op Amp**

1. **Voltage Measurements:**
   
   Vo vs. Vi data was collected for at least 9 Vi values ranging from negative to positive saturation points (-15V to 15V). The corresponding Vo values were recorded, and a graph was prepared, showing the lab data as scattered points around the expected gain line. The potentiometer was adjusted to Vi = -15, -14, -12, -5, 0, 5, 12, 14, 15, then Vo was measured. Figure 14 describes the technique used to change the resistance value of the 10 kΩ potentiometer.

<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/c3f1a1d9-a926-455f-b542-f99bfec9acda" alt "Circuit 1" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 14: Altering the resistance of the 10kΩ potentiometer. </figcaption>
</div>

<br>

**Part 1.2: Moderate Gain Inverting Op Amp Circuit**

1. **Voltage Measurements:**
 
  The oscilloscope was used to plot Vi on channel 1 and Vo on channel 2. The gain of the circuit was measured and calculated using the oscilloscope. The observed o-scope display is provided in Figure 15.

<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/b524aa6d-455b-4cc4-b844-3d1d2aeb82de" alt "Oscope Gain" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 15: Display on o-scope when plotting Vi and Vo on separate channels. </figcaption>
</div>

   To calculate gain, the Channel 1 voltage (Vi) and the Channel 2 voltage (Vo) were found using the oscilloscope. Then, using the formula provided below the gain was calculated for the circuit.

   <div align="center"> Gain = (Vo) / (Vi) </div>


<br>
**Part 1.3: High-Gain Inverting Op Amp Circuit**

   1. **Voltage Measurements:**
  The oscilloscope was used to plot Vi on channel 1 and Vo on channel 2. The gain of the circuit was measured and calculated using the oscilloscope. The o-scope display for this circuit was similar to what was shown in the previous Figure 15 and the same procedure was used to calculate gain.


<br> 

**Part 2.1: Voltage Follower Circuit**

   The oscilloscope was used to check whether the input and output voltage were the same. Vo vs. Vi data was collected, and the gain for this circuit was calculated. The frequency was increased to determine and record the frequency limit for the op amp.
   
<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/0343927d-d9eb-4dce-98fa-5275dc572136" alt "Function Generator" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 16: Function Generator for increasing frequency to find the op amp frequency limit. </figcaption>
</div>


**Part 2.2: Integrating Op Amp Circuit**
   The function generator was used to observe and sketch or capture images of the input and output waveforms for 4 kHz, 1Vp-p, sine, square, and triangle waves. Voltage and frequency were varied, and differences were noted.

<br>

The o-scope display for the sine wave is shown in Figure 17 below.

<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/70fde8c2-5680-46c5-9098-d5371c6bb318" alt "Sine wave Circuit 5" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 17: Sine wave output for integrating op-amp circuit. </figcaption>
</div>

The o-scope display for the square wave is shown in Figure 18 below.

<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/3516ec5c-244c-4a1c-9120-a5e748cdac0c" alt "Square Wave Circuit 5" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 18: Square wave output for integrating op-amp circuit. </figcaption>
</div>

The o-scope display for the triangle wave is shown in Figure 19 below.

<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/21d84b60-d061-4f1b-ab17-345b21b9a0f5" alt "Triangle Wave Circuit 5" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 19: Triangle wave output for integrating op-amp circuit. </figcaption>
</div>

   Additionally, the relationship between the wave output, amplitude, and frequency was observed. Figure 20 shows how the o-scope display responds to decreasing frequency, and Figure 20 describes the effect of increasing amplitude. It was noted that as the frequency increased, so did the voltage, whereas when the frequency was decreased, the voltage decreased.

<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/c52bb2b4-9426-444e-9cca-b311ebf6d8a5" alt "Dec Frequency for Circuit 5" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 20: Decreasing frequency wave o-scope display. </figcaption>
</div>   


<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/b122ffe4-abda-415f-a699-1c56f5c854e2" alt "Inc Amplitude for Circuit 5" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 21: Increasing amplitude of wave o-scope display. </figcaption>
</div>  
<br>

**Part 2.3: Differentiating Op Amp Circuit**
   The function generator was used to observe and sketch the input and output waveforms for 1 kHz, 2Vp-p, sine, square, and triangle waves. Voltage and frequency were varied, and differences were noted.

<br>

The o-scope display for the sine wave is shown in Figure 22 below.

<br>
<div align= "center">
<img src="hhttps://github.com/user-attachments/assets/c750b07d-cdd7-4e06-a770-52fd73f9cb5d" alt "Sine wave Circuit 6" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 22: Sine wave output for integrating op-amp circuit. </figcaption>
</div>

The o-scope display for the square wave is shown in Figure 23 below.

<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/6aeb3c5e-d3eb-48da-9bab-c91cdf5665bb" alt "Square Wave Circuit 6" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 23: Square wave output for integrating op-amp circuit. </figcaption>
</div>

The o-scope display for the triangle wave is shown in Figure 24 below.

<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/a9e0e3f0-ffd1-41b2-8095-cd032a79953e" alt "Triangle Wave Circuit 6" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 24: Triangle wave output for integrating op-amp circuit. </figcaption>
</div>

   Just like in Part 2.2, the relationship between the wave output, amplitude, and frequency was observed. Figure 25 shows how the o-scope display responds to increasing frequency, and Figure 26 describes the effect of increasing amplitude. It was noted that as the frequency increased, so did the voltage, whereas when the frequency was decreased, the voltage decreased.

<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/436c0218-0219-4276-8245-e2222432c82c" alt "Inc Frequency for Circuit 6" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 25: Increasing frequency wave o-scope display. </figcaption>
</div>


<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/14e29e7b-22b2-4193-9b4c-8f5bffec1bc9" alt "Inc Amplitude for Circuit 6" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 26: Increasing amplitude of wave o-scope display. </figcaption>
</div>  
<br>

## Test Results:

**Table 1: Resistor Values**

| Resistor # | Expected Resistance (Ohms) | Tolerance | Max Value (Ohms) | Min Value (Ohms) | Measured Resistance (Ohms) |
|------------|----------------------------|-----------|------------------|------------------|-----------------------------|
| 1          | 270000                     | 5%        | 283500           | 256500           | 267200                      |
| 2          | 8200                       | 5%        | 8610             | 7790             | 8110                        |
| 3          | 68000                      | 5%        | 71400            | 64600            | 67100                       |
| 4          | 68000                      | 5%        | 71400            | 64600            | 66800                       |
| 5          | 330000                     | 5%        | 346500           | 313500           | 330600                      |
| 6          | 1500000                    | 5%        | 1575000          | 1425000          | 1492000                     |
| 7          | 150000                     | 5%        | 157500           | 142500           | 147500                      |
| 8          | 1000                       | 5%        | 1050             | 950              | 988                         |
| 9          | 22000                      | 5%        | 23100            | 20900            | 21810                       |
| 10         | 4700                       | 5%        | 4935             | 4465             | 4652                        |
| 11         | 1000                       | 5%        | 1050             | 950              | 978                         |
| 12         | 22000                      | 10%       | 24200            | 19800            | 21030                       |
| 13         | 220000                     | 5%        | 231000           | 209000           | 218200                      |

**Part 1 Results:**

**Table 2: Unity Gain Inverting Op Amp Voltages**

| Target Vi (V) | Measured Vi (V) | Measured Vo (V) |
|---------------|-----------------|-----------------|
| -15           | -14.98          | 14.25           |
| -14           | -13.99          | 13.96           |
| -12           | -12.02          | 12              |
| -5            | -5.01           | 5.002           |
| 0             | 0.001           | 0.018           |
| 5             | 4.997           | -4.97           |
| 12            | 12.02           | -11.97          |
| 14            | 14              | -12.92          |
| 15            | 14.99           | -12.91          |

**Table 3: Moderate Gain Inverting Op Amp Oscilloscope Readings**

| Channel 1 (Vi) (mV) | Channel 2 (Vo) (mV) |   Gain   |
|---------------------|---------------------|----------|
| 101.6               | 4.2                 | 41.33    |

**Table 4: High Gain Inverting Op Amp Oscilloscope Readings**

| Channel 1 (Vi) (mV) | Channel 2 (Vo) (mV) |   Gain   |
|---------------------|---------------------|----------|
| 32.4                | 16.56               | 511.11   |

**Part 2 Results:**

**Table 5: Voltage Follower Op Amp Oscilloscope Readings**

| Channel 1 (Vi) (mV) | Channel 2 (Vo) (mV) |   Gain   |
|---------------------|---------------------|----------|
| 1.088               | 160                 | 0.147    |

**Table 6: Voltage Follower Op Amp Frequency Limit**
| Frequency Limit (mHz) |
|-----------------------|
| 4.3                   |

**Table 7: Integrating Op Amp Oscilloscope Readings**

| Channel 1 (Vi) (mV) | Channel 2 (Vo) (mV) |   Gain   |
|---------------------|---------------------|----------|
| 1.088               | 160                 | 0.147    |

**Table 8: Differentiating Op Amp Oscilloscope Readings**

| Channel 1 (Vi) (mV) | Channel 2 (Vo) (mV) |   Gain   |
|---------------------|---------------------|----------|
| 1.088               | 160                 | 0.147    |



## Discussion:

Part 1.1: 

describe performance curve for potentiometer. you will need to plot this on the excel and add the figure after Table 8.
Prepare a graph showing the lab data as scattered points around the line for the expected gain
(consider actual resistor values


<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/ce586e1d-b791-4319-a63a-db7b605d4bc1" alt "Vo vs. Vi" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 27: Vo vs. Vi. </figcaption>
</div>

We analyzed the performance curve for the potentiometer by plotting the measured Vi vs. Vo values from Table 2. The graph demonstrates a nearly linear relationship, confirming that the unity gain inverting amplifier behaves as expected within its operational range. However, as the input voltage approaches the saturation limits of the op-amp, the output deviates from the ideal linear response due to the inherent voltage limitations of the LM741. This behavior aligns with the expected characteristics of an operational amplifier nearing saturation. The plotted data was included in Excel and placed after Table 8.

Rest of Part 1: 

Compare the performance of each amplifier circuit to its expected theoretical performance with
regard to gain.

We compared the experimental gain values for the moderate and high-gain inverting op-amp circuits with the theoretical values calculated using resistor ratios. The theoretical gain for the moderate gain circuit, based on the expected resistor values, was approximately -68, but our measured gain was 41.33. Similarly, the high-gain circuit had an expected gain of -1500 but a measured gain of 511.11. These discrepancies can be attributed to component tolerances, parasitic resistances, and the limited open-loop gain of the LM741, which reduces its effectiveness at high gains.


b. Comment on the limits of op-amp circuits with respect to maximum output voltage.

We observed that the LM741 does not output its full power supply range due to internal design constraints. As shown in Table 2, the output voltage saturates at approximately ±12.9V rather than reaching the full ±15V supply rails. This behavior is a known limitation of the LM741, which typically has a voltage swing of about 2-3V less than the supply rails. This limitation must be considered in practical applications where maximizing the dynamic range is essential.


c. Are the LM741 op amps symmetric i.e. does the positive voltage performance equal the
negative voltage performance?

Our Vo vs. Vi graph indicates that the LM741 does not exhibit perfect symmetry in positive and negative voltage performance. While the output voltage generally follows the expected inverted relationship, we noticed minor differences in the absolute values of positive and negative outputs. These variations arise due to internal offsets, manufacturing tolerances, and asymmetrical sourcing and sinking capabilities of the output stage. Though small, these differences can impact precision applications.
Part 2.1: 


discuss frequency limit

We tested the voltage follower circuit to determine the frequency at which it could no longer maintain a stable output. The measured frequency limit was found to be 4.3 MHz, as recorded in Table 6. This result is unexpectedly high given that the LM741 has a typical gain-bandwidth product of approximately 1 MHz. The discrepancy is likely due to a user error in measurement, possibly from incorrect oscilloscope settings or a misunderstanding of the measuring procedure.

Rest of Part 2:

Did the integrating and differentiating circuits perform the mathematical operations expected?
Explain.

We analyzed the integrating and differentiating circuits using various input waveforms, including sine, square, and triangle waves. The integrating circuit successfully transformed:
- Sine waves into cosine waves (consistent with integration)
- Square waves into triangular waves
- Triangle waves into parabolic-like curves
  
Similarly, the differentiating circuit demonstrated expected behavior by converting:

- Sine waves into cosine waves
- Triangle waves into square waves
- Square waves into sharp spikes, characteristic of differentiation
  
These results confirm that our circuits performed their intended mathematical operations. However, at higher frequencies, distortions were observed, likely due to limitations in the LM741’s bandwidth and phase shifts introduced by non-ideal component characteristics. This highlights the importance of selecting op-amps with appropriate frequency response for high-speed applications.


## Conclusion:


