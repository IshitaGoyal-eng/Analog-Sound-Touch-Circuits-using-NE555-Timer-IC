# Analog-Sound-Touch-Circuits-using-NE555-Timer-IC
A collection of analog hardware projects built using the NE555 Timer IC, demonstrating practical applications in audio frequency generation and touch-based triggering systems.

This repository includes:

🔔 Touch-Sensitive Buzzer with Latching Mechanism

🎹 Mini Analog Piano (7-Key)

# PROJECT 1:🔔 Touch-Sensitive Buzzer using NE555 Timer IC

## Overview
A touch-activated buzzer circuit built using the NE555 timer IC.  
The system detects human touch to trigger a buzzer and LED, and includes  
a latching mechanism that keeps the alarm ON until manually reset.

## Components Used
| Component        | Value/Type          |
|------------------|---------------------|
| Timer IC         | NE555               |
| Transistor       | BC547 (NPN)         |
| Buzzer           | Active Buzzer       |
| Resistors        | As per design       |
| Push Button      | Manual Reset Switch |
| Power Supply     | 5–12V DC            |
| PCB              | Zero PCB            |

## Working Principle
- Human touch provides a small trigger voltage to **Pin 2** of NE555  
- NE555 output goes HIGH, activating the buzzer and LED  
- BC547 transistor creates a **latching feedback path** to maintain HIGH output  
- Manual reset switch connected to **Pin 4** turns the buzzer OFF  

## Project Workflow
1. Circuit designed and validated  
2. Prototyped and tested on **breadboard**  
3. Final circuit soldered onto **Zero PCB**  

## Output
- Buzzer and LED activate on human touch  
- Latching mechanism keeps alarm ON after touch removal  
- Manual reset functionality tested and verified  


## 🛠 Technologies & Tools
- NE555 Timer IC (Astable & Monostable Modes)  
- LTSpice Simulation  
- BC547 Transistor  
- Zero PCB Fabrication  
- Hardware Testing & Debugging  


# PROJECT 2: Mini Analog Piano 🎹 using NE555 Timer IC

## Overview
A functional 7-key analog piano circuit built using the NE555 timer IC 
configured in astable mode. Each key produces a distinct musical tone 
by varying the oscillation frequency through unique resistor values.

## Components Used
| Component        | Value/Type         |
|------------------|--------------------|
| Timer IC         | NE555              |
| Resistors        | 1kΩ (×10), 4.7kΩ  |
| Capacitors       | 100nF, 10µF        |
| Push Buttons     | 7× Momentary Switch|
| Speaker/Buzzer   | 12V                |
| PCB              | Zero PCB           |

## Working Principle
- NE555 configured in **astable mode** generates continuous square waves
- Each push button introduces a **unique resistor** into the timing circuit
- Changing resistance changes the **oscillation frequency** → changes pitch
- Output drives a buzzer/speaker to produce the corresponding musical note

## Project Workflow
1. 📐 Circuit designed and simulated in **LTSpice**
2. 🔌 Prototyped and tested on **breadboard**
3. 🔧 Final circuit soldered onto **Zero PCB**

## Output
✅ 7 distinct audio tones successfully generated  
✅ Stable output verified through LTSpice waveform analysis  
✅ Final circuit fabricated and tested on Zero PCB  

## Learnings
- Astable mode configuration of NE555 timer
- Relationship between RC values and output frequency
- PCB soldering and hardware debugging


