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

   When constructed, the circuit assembled using Schematic 2 should resemble Figure 4.

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

   Unfortunately, our group did not take a photo of the constructed circuit for Schematic 3, but when constructed, the circuit assembled using Schematic 3 should have the same setup as the previous circuit in Figure 5, but with resistors values of 1.5 MΩ and 1 kΩ. 
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
  <img src="[https://github.com/user-attachments/assets/0a8a5f82-c6f0-4582-8a80-a51c4bc0ef43](https://github.com/user-attachments/assets/1e3d7d5b-bb39-4b12-9abe-971e10933cd9)" alt="Assembled voltage follower op amp circuit" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 8: Constructed voltage follower op amp circuit from Figure 7. </figcaption>
</div>

2.2. **Integrating Op Amp Circuit**

   The integrating op amp circuit was assembled according to the schematic given in Figure . The function generator was connected to Vi.

<div align="center">
<img src="https://github.com/user-attachments/assets/4efbc658-43d3-44e1-a12a-e7e4daccd3dd" alt="Schematic 4" width="400">
<br/>

<figcaption style="font-size: 16px; text-align: center;"> Figure 9: Transistor controlled motor current and speed schematic. </figcaption>
</div>   

<br/>
  Once assembled, the circuit should look resemble Figure 8 below.

   <div align="center">
  <img src="https://github.com/user-attachments/assets/d2981ce5-c15f-4577-a524-8122d3324fc7" alt="Assembled parallel resistor circuit" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 10: Transistor controlled motor current and speed schematic. </figcaption>
</div>

<br>

2.3. ** Differentiating Op Amp Circuit**
   The differentiating op amp circuit was built following the schematic shown in Figure 11. The function generator was connected to Vi.


<div align="center">
<img src="https://github.com/user-attachments/assets/db1927d1-b8ee-47f9-a5d6-02810c6a91e9" alt="Schematic 4" width="400">
<br/>

<figcaption style="font-size: 16px; text-align: center;"> Figure 11: Differentiating op amp schematic. </figcaption>
</div>   

<br/>
  Once assembled, the circuit should look resemble Figure 8 below.

   <div align="center">
  <img src="https://github.com/user-attachments/assets/d2981ce5-c15f-4577-a524-8122d3324fc7" alt="Assembled parallel resistor circuit" width="400">
      <br/>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 12: Constructed differentiating op amp schematic. </figcaption>
</div>
<br>

## Test Equipment

1. Fluke 87 V DMM
2. DC Power Supply
   
## Test Procedures

**Resistor Measurement**

   For this part of the experiment, the resistance each resistor was measured using a Digital Multimeter (DMM) and the results were compared to the expected values based on the resistor color codes. We recorded the expected resistance, the acceptable tolerance range, and the measured resistance in a table. Any resistors that fell outside the expected range were noted.

**Part 1.1: Unity Gain Inverting Op Amp**

1. **Voltage Measurements:**
   
   Vo vs. Vi data was collected for at least 9 Vi values ranging from negative to positive saturation points (-15V to 15V). The corresponding Vo values were recorded, and a graph was prepared, showing the lab data as scattered points around the expected gain line. The potentiometer was adjusted to Vi = -15, -14, -12, -5, 0, 5, 12, 14, 15, then Vo was measured. Figure 12 describes the technique used to change the resistance value of the 10 kΩ potentiometer.

<br>
<div align= "center">
<img src="https://github.com/user-attachments/assets/c3f1a1d9-a926-455f-b542-f99bfec9acda" alt "Circuit 1" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 12: Altering the resistance of the 10kΩ potentiometer. </figcaption>
</div>

<br>


**Part 1.2: Moderate Gain Inverting Op Amp Circuit**

1. **Voltage Measurements:**
 
  The oscilloscope was used to plot Vi on channel 1 and Vo on channel 2. The gain of the circuit was measured and calculated using the oscilloscope.


<div/>
   
**Part 1.3: High-Gain Inverting Op Amp Circuit**

   1. **Voltage Measurements:**
  The oscilloscope was used to plot Vi on channel 1 and Vo on channel 2. The gain of the circuit was measured and calculated using the oscilloscope.

**Part 2.1: Voltage Follower Circuit**

   The oscilloscope was used to check whether the input and output voltage were the same. Vo vs. Vi data was collected, and the gain for this circuit was estimated. The frequency was increased to determine and record the frequency limit for the 741 op amp.

**Part 2.2: Integrating Op Amp Circuit
   The function generator was used to observe and sketch or capture images of the input and output waveforms for 4 kHz, 1Vp-p, sine, square, and triangle waves. Voltage and frequency were varied, and differences were noted.

**Part 2.3: Differentiating Op Amp Circuit**
   The function generator was used to observe and sketch the input and output waveforms for 1 kHz, 2Vp-p, sine, square, and triangle waves. Voltage and frequency were varied, and differences were noted.

 
## Test Results:

**Table 1: Resistor Values**

| Resistor # | Expected Resistance (Ohms) | Tolerance | Max Value (Ohms) | Min Value (Ohms) | Measured Resistance (Ohms) |
|------------|----------------------------|-----------|------------------|------------------|----------------------------|
| 1          | 2.2                        | 5%        | 2.31             | 2.09             | 2.24                        |
| 2          | 270                        | 5%        | 283.5            | 256.5            | 268.9                       |
| 3          | 1000                       | 5%        | 1050             | 950              | 984                         |

**Table 2: DCPS Voltage Verification**
| Expected DCPS Voltage Output (V) | Measured Voltage with DMM (V) |
|----------------------------------|-------------------------------|
| 5                                | 5.01                          |

**Table 3: LED Directly Controlled by a Switch**

| Test Point |     Voltage (Switch On)     |     Voltage (Switch Off)     |
|------------|-----------------------------|------------------------------|
| T2         | 2.045 V                     | 0.163 V                      |
| T3         | 0 V                         | 0  V                         |

| Component  |  Voltage Across (Switch On) |  Voltage Across (Switch Off) |
|------------|-----------------------------|------------------------------|
| R1         | 2.95 V                      | 0 V                          |
| LED1       | 2.05 V                      | 0.171 V                      |
| S1         | 0 V                         | 0 V                          |

|            | Current Through (Switch On) | Current Through (Switch Off) |
|------------|-----------------------------|------------------------------|
| LED1       | 0.012 A                     | 0 A                          |

**Table 4: LED Controlled by a Transistor**

| Test Point |     Voltage (Switch On)    |     Voltage (Switch Off)      |
|------------|----------------------------|-------------------------------|
| T2         | 2.047 V                    | 5.003 V                       |
| T3 (VCE)   | 0.013 V                    | 3.518 V                       |
| T5 (VBE)   | 0.682 V                    | 0.170 V                       |
| T6         | 5 V                        | 0.135 V                       |

| Component  | Voltage Across (Switch On) |  Voltage Across (Switch Off)  |
|------------|----------------------------|-------------------------------|
| R1         | 2.914 V                    | 0 V                           |
| LED1       | 2.045 V                    | 0.390 V                       |
| R2         | 4.4 V                      | 0 V                           |
| S1         | 0 V                        | 0 V                           |

|            | Current Through (Switch On) | Current Through (Switch Off) |
|------------|-----------------------------|------------------------------|
| LED1 (IC)  | 0.012 A                     | 0 A                          |
| R2 (IB)    | 0.005 A                     | 0 A                          |


**Table 5: Adjusting LED Brightness with a Transistor**

|  Test Point |     Dim LED Voltage    |     Midpoint 1 Voltage    |     Midpoint 2 Voltage    |     Bright LED Voltage    |
|-------------|------------------------|---------------------------|---------------------------|---------------------------|
| T2          | 4.97 V                 | 4.86 V                    | 2.62 V                    | 2.057 V                   |
| T3 (VCE)    | 3.26 V                 | 3.063 V                   | 0.530 V                   | 0.011 V                   |
| T5 (VBE)    | 0.459 V                | 0.515 V                   | 0.592 V                   | 0.683 V                   |
| T6          | 0.459 V                | 0.518 V                   | 0.625 V                   | 4.992 V                   |

|  Component  | Voltage Across Dim LED | Voltage Across Midpoint 1 | Voltage Across Midpoint 2 | Voltage Across Bright LED |
|-------------|------------------------|---------------------------|---------------------------|---------------------------|
| R1          | 0.015 V                | 0.130 V                   | 2.46 V                    | 2.94 V                    |
| LED 1       | 1.709 V                | 1.804 V                   | 2.015 V                   | 2.041 V                   |
| R2          | 0 V                    | 0.002 V                   | 0.033 V                   | 4.309 V                   |

|             | Current Through Dim LED| Current Through Midpoint 1| Current Through Midpoint 2| Current Through Bright LED|
|-------------|------------------------|---------------------------|---------------------------|---------------------------|
| LED (IC)    | 0.00007 A              | 0.00045 A                 | 0.00901 A                 | 0.01077 A                 |
| R2 (IB)     | 0.00001 A              | 0.00001 A                 | 0.00004 A                 | 0.00505 A                 |
| Gain (IC/IB)| 7                      | 45                        | 225.25                    | 2.132                     |

**Table 6: Motor Speed Control Using a Transistor**

|  Test Point |     Slow Motor Voltage    |     Midpoint 1 Voltage    |     Midpoint 2 Voltage    |     Fast Motor Voltage    |
|-------------|---------------------------|---------------------------|---------------------------|---------------------------|
| T2          | 4.825 V                   | 4.77 V                    | 4.74 V                    | 4.710 V                   |
| T3 (VCE)    | 2.917 V                   | 1.25 V                    | 0.476 V                   | 0.125 V                   |
| T5 (VBE)    | 0.633 V                   | 0.654 V                   | 0.669 V                   | 0.713 V                   |
| T6          | 0.847 V                   | 0.925 V                   | 1.0 V                     | 4.960 V                   |

|  Component  | Voltage Across Slow Motor | Voltage Across Midpoint 1 | Voltage Across Midpoint 2 | Voltage Across Fast Motor |
|-------------|---------------------------|---------------------------|---------------------------|---------------------------|
| R1          | 0.160 V                   | 0.198 V                   | 0.215 V                   | 0.238 V                   |
| M1          | 2.16 V                    | 3.459 V                   | 3.553 V                   | 4.6 V                     |
| R2          | 0.215 V                   | 0.274 V                   | 0.270 V                   | 4.25 V                    |

|             | Current Through Slow Motor| Current Through Midpoint 1| Current Through Midpoint 2| Current Through Fast Motor|
|-------------|---------------------------|---------------------------|---------------------------|---------------------------|
| M1 (IC)     | 0.0642 A                  | 0.0815 A                  | 0.10001 A                 | 0.108 A                   |
| R2 (IB)     | 0.00019 A                 | 0.00029 A                 | 0.00048 A                 | 0.00433 A                 |
| Gain (IC/IB)| 337.894                   | 281.034                   | 208.354                   | 24.942                    |

## Discussion:


**Discussion Question 1: How does the current through the LED compare between circuits 1 and 2?**

The current through the LED was nearly the same in both circuits. In Circuit 1, where the LED was directly connected to the switch, the measured current (Ic) was 0.012 A when the switch was on. In Circuit 2, where the LED was driven by a transistor, the current was also 0.012 A. This means that adding the transistor didn’t significantly change the LED current. 



**Discussion Question 2: How does your measured VCE compare to the one listed in the datasheet? Are we in the saturation region?**

The TIP31C datasheet lists a maximum saturation voltage (VCE(sat)) of 1.2V, but our measured value was 0.013V when the LED was on. Since this is much lower than the datasheet value, it indicates that the transistor is in deep saturation. A transistor in saturation acts like a closed switch, meaning there is very little voltage drop between the collector and emitter. To confirm this, we adjusted the power supply slightly and saw that the collector current (Ic) remained mostly the same. This behavior is expected when the transistor is fully saturated.



**Discussion Question 3: What happens to IC as you change the voltage?**

As the base voltage (T6) increased, the current through the LED (Ic) also increased, making the LED brighter. At 0.459V, the collector current was 0.00007 A, which barely lit the LED. When the base voltage increased to 0.518V, the collector current rose to 0.00045 A, and the LED appeared much brighter. This shows that even a small change in base voltage can lead to a noticeable difference in current, which is a key feature of transistor operation. Essentially, the transistor is amplifying the small input signal at the base to control a larger current through the LED.



**Discussion Question 4: What is the voltage drop (VCE) across the transistor (Q1) when the motor is in the fast setting? How does this compare with the LED circuit?**

When the motor was running at full speed, the measured VCE was 1.25V. This is quite a bit higher than the VCE measured in the LED circuit, which was only 0.013V. The reason for this difference is that the motor requires more current than the LED, which affects how the transistor operates. In the LED circuit, the transistor was in deep saturation with a very low VCE. In the motor circuit, the transistor was likely still in saturation but with a higher voltage drop due to the increased load.



**Discussion Question 5: How much current is going through the motor in the fast setting? How does this compare to the LED circuit? Could the switch alone support the motor?**

At full speed, the motor drew 0.0815 A, which is much more than the 0.012 A needed for the LED. The gain (Ic/Ib) for the motor circuit was around 281, while in the LED circuit, it was about 45. This difference shows that the motor required significantly more current than the LED. Since the switch barely handled the LED’s current, it definitely wouldn’t be able to power the motor directly. The transistor switch is necessary here because it allows the motor to pull a higher current from the power supply while still being controlled by a low-power input.

## Conclusion:

This lab showed how bipolar junction transistors (BJTs) work as switches in circuits with an LED and a motor. By measuring voltage and current, we saw how the transistor’s gain (β) impacts circuit performance. The potentiometer allowed us to adjust the current, demonstrating how transistors can control more than just on/off states. We also used a diode to protect the motor from voltage spikes. These experiments helped us understand how transistors function in real-world circuits and why they are important in electronic design.
