# Sarna Ma'am's Part

## [[Slide] Peripherals and Interfaces-01](https://t.me/c/1734256119/3086/3097)

- Buffers and Spoolers
- Interface Standards
- Wireless Communication
- Microprocessor Data Type
	- Signed
		- Signed magnitude
		- 1's complement
		- 2's complement
	- Floating Point Number
		- Exponent value implemented in bits
- Main Memory Array Design
	- Linear Decoding
	- Using Decoder
	- Programmable Array Logic
		- PLDs
			- PROM
			- PAL
			- PLA
- Example: 01
- Example: 02


## [[Book] Rafiquzzaman - 1st Chapter](https://t.me/c/1734256119/3086/3122)

- Input-Output Interfacing [Page:11 of PDF]
	- Programmed I/O
	- Interrupt Driven I/O
	- DMA


> **Rafiquzzaman - 1st Chapter (Exercise) + Slide** $\star \star \star$


## [[Slide] Interfacing Keyboard](https://t.me/c/1734256119/3086/3095)

### Math [from Slide:25]

- **Interface a 4 $\times$ 4 keyboard with 8086 using 8255 and write an ALP for detecting a key closure and return the key code in AL. The debounce period for a key is 10ms. Use software debouncing technique. DEBOUNCE is an available 10ms delay routine.** $\star \star \star$

## [[Book] Chapter 2 : Image Representations (from Computer Graphics)](https://t.me/c/1734256119/3086/3291)

- Display
- Image Resolution
- Aspect Ratio
- Refresh Buffer

### 2.1 The RGB Color Model
- RGB (Red Green Blue)
	- Additive
	- Monitor

- CMY (Cyan Magenta Yellow)
	- Substractive
	- Printer

### 2.2 Direct Coding

24 bit $\to$ True Color

### 2.3 Lookup Table

### 2.4 Display Monitor

CRT Monitor:

- Cathode Ray Tube
	- Hit $\to$ Florosence
	- Light up	$\to$ Phosphorosence
	- Time it lighted up $\to$ Persistance of Phosphor
- Persistance $\geq$ Refresh Rate 

> **Why 60 Hz?** <br/>
CRT differs from LCD or LED.

#### Color Display


## [[Slide] Display Basics](https://t.me/c/1734256119/3086/3099)

## [[Slide] 8255 PPI](https://t.me/c/1734256119/3086/3100)

## [[Slide] Printer](https://t.me/c/1734256119/3086/3101)

## [[Slide] 8279 Programmable Keyboard Display Controller](https://t.me/c/1734256119/3086/3096)


# Arpita Ma'am's Part

## [[Slide] Lecture 1 IoT-Week1-Day1](https://t.me/c/1734256119/3086/3274)

## [[Sheet] Module 2 - Sensors and Signal Processing](https://t.me/c/1734256119/3086/3275)

- Lecture 1 - Sensors and transducers
	- Sensor
	- Transducer
	- Sensor/transducers specifications
		1. Range
		2. Span
		3. Error
		4. Accuracy
		5. Sensitivity
		6. Nonlinearity
		7. Hysteresis
		8. Resolution
		9. Stability
		10. Dead band/time
		11. Repeatability
		12. Response time
	- Classification of sensors
		- Displacement, position and proximity sensors
		- Velocity and motion
		- Force
		- Fluid pressure
		- Liquid flow
		- Liquid level
		- Temperature
- Lecture 2 - Displacement and position sensors
	1. Potentiometer Sensors
	2. Strain Gauges
	3. Capacitive element based sensor
	4. Linear Variable Differential Transformer (LVDT)
		- Rotary Variable Differential Transformer (RVDT)
			- Connections from *Inductive Proximity Switch*
- Lecture 3 - Displacement, position and proximity sensors
	1. Eddy current proximity sensors
	2. Inductive proximity switch
	3. Optical encoders
	4. Pneumatic Sensors
		- *Pneumo* relating to air
	5. Proximity Switches
	6. Hall effect sensor
- Lecture 4 - Velocity, motion, force and pressure sensors
	1. Tachogenerator
	2. Pyroelectric sensors
	3. Strain Gauge as force Sensor
	4. Fluid pressure
	5. Tactile sensors
	6. Piezoelectric sensor
	7. Liquid flow
	8. Fluid level

## [[Slide] Lecture-2 (WSN) WSN Taxonomy on Communication & Power](https://t.me/c/1734256119/3086/3357)

> (till: Slide-17 Packet Switching)

- Wireless Sensor Networks
- Roles of Participants in WSN
- Deployment Options for WSN
- Maintenance Options
- Characteristic Requirements for WSNs
- Required Mechanisms to Meet Requirements
- Enabling Technologies for WSN
- Types of Radio Networks
- Communication basics
- Signals propagate in medium, store data
- Basic organization of communication
- Multiplexing & shared resources
- How to realize multiple hops: Switching
- Packet Switching

## [[Slide] Lecture-3 (WSN) Personal Area Network (PAN) Protocol – Medium Access Control (MAC)](https://t.me/c/1734256119/3086/3395)

>(till: Slide-29 RTS/CTS)

- Multiple Access
- Taxonomy of Multiple-access Protocols
- Medium Access Control (MAC)
- Main Options
- Principal Options and Difficulties
- Requirements for Energy-efficient MAC
- Centralized Medium Access
- Schedule- vs. Contention-based MACs
- Random Access
- ALOHA - Analysis, Performance
- ALOHA network – Multiple Access
- A Slight Improvement: Slotted ALOHA
- Performance dependence on offered load
- Carrier Sense Multiple Access (CSMA)
- Problems for the CSMA MAC-Protocol
	- **Hidden Terminal Problem** $\star \star \star$
	- Exposed Terminal Problem
- Distributed, contention-based MAC
- Main Options to Shut-up Senders
- Multiple Access with Collision Avoidance (MACA) / CSMA-CA
- RTS/CTS

## [[Slide] Lecture-4 (WSN-Synchronous MAC) Synchronous MAC Protocols for Wireless Sensor Networks](https://t.me/c/1734256119/3086/3394)

- Synchronous MAC Protocols
	- S-MAC (Sensor MAC) Protocol
		- Problems Identified for Energy Waste
		- Idea
			- ***Definition:* sleeping time, wake up time** $\star \star \star$
		- Synchronized Islands / Virtual Cluster
		- Problems of S-MAC
	- T-MAC (Time-out MAC) Protocol
		- Issues Handled
		- Idea
		- T-MAC Operation
		- Problems of T-MAC
	- D-MAC Protocol
		- Issues Handled in D-MAC
			- Single Channel Directional
			- Multi Channel Directional
		- Sleep Delay Problem
		- Idea of D-MAC
		- Problems of D-MAC