Certainly! Here's the README file with images embedded:

# Project Title: Thermal Design and Simulation of LM308N Amplifier Circuit

## Overview:
This project was conducted as part of the laboratory work for the course "Microelectronics and Packaging Techniques" in the 7th semester. The team, consisting of Vaidanis Symeon, Hliopoulos Georgios, Ratsas Ilias, and Spanos Nikolaos, aimed to design an amplifier circuit using the LM308N integrated circuit.

## Circuit Design:
The chosen circuit configuration is an inverting amplifier with high input resistance. The gain (AV) of the amplifier is determined by the formula:
\[ AV = \frac{R2}{(R3 + R4) \times R1 \times R3} \]

## Tools Used:
- **Eagle:** The initial circuit design was done using the Eagle software.
- **Fusion 360:** The board layout was designed in Fusion 360 to visualize the 3D model.
- **SimScale:** Thermal analysis of the board was performed using SimScale.

## Circuit Components:
- **Amplifier:** LM308N
- **Resistors:** R-EU0207/10 series
- **Capacitor:** CPOL-EUE1.8-4

## Board Layout:
The team used Eagle for the schematic design, and the board layout was created with tools like Polygon, Ratsnest, and Route airway.

**Image 3: Circuit in Eagle**
![Circuit in Eagle](path/to/image3.png)

## 3D Model:
The board was modeled in 3D using Autodesk Fusion 360, providing a comprehensive view from different angles.

**Image 5: 3D Model in Fusion 360**
![3D Model in Fusion 360](path/to/image5.png)

## Thermal Analysis:
To enhance thermal performance, heatsinks were added to the LM308N. Various heatsinks were experimented with, and the best results were obtained with heatsink hs7.

**Image 6: Heatsink on LM308N**
![Heatsink on LM308N](path/to/image6.png)

The thermal analysis was performed using SimScale, with results shown below.

**Image 7: Thermal Analysis Results**
![Thermal Analysis Results](path/to/image7.png)

## Results and Conclusion:
The thermal analysis revealed that while heatsinks significantly reduced the temperature of the integrated circuit, achieving the optimal operating temperature range specified in the LM308N datasheet was challenging. Despite this, the heatsink demonstrated efficiency in cooling a portion of the IC.

*Note: Detailed dimensions, resistor values, and other specifics are available in the full report.*
