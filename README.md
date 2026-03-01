# Real-Time Interactive LED Piano System

## 📌 Project Overview
This project presents the design and implementation of a real-time interactive LED rhythm piano system based on Arduino and LabVIEW. The system integrates LED visualization, touch sensing, scoring logic, and audio output to simulate a physical rhythm game interface.

## 🏗 System Architecture
The system consists of two main modules:

- Arduino: Controls the WS2812 LED strip and generates timing signals.
- NI ELVIS + LabVIEW: Acquires touch sensor signals, performs scoring logic, and generates audio output.

### Signal Flow
User Input → Touch Sensor → NI ELVIS (DAQ) → Scoring Logic → 
- Seven-Segment Display (Score Output)
- PC Speaker (Audio Output)

Arduino → LED Control → Timing Signal → NI ELVIS

## 🔧 Hardware Components
- Arduino
- NI ELVIS
- WS2812 LED Strip
- Capacitive Touch Sensors
- Seven-Segment Display
- Breadboard and Corrugated Board Structure

## 💻 Software Implementation
- Arduino (FastLED Library)
- LabVIEW (DAQ Assistant)
- Multi-channel signal acquisition
- Synchronous scoring logic
- Audio frequency mapping

## 🎮 Gameplay Logic
- LED signals fall from top to bottom.
- User must press the corresponding key at the correct timing.
- Score increases only when LED signal and key press are detected simultaneously.
- 800 ms delay prevents repeated scoring.

## ⚙ Key Features
- Real-time LED visualization
- Beat-synchronized scoring system
- Multi-channel signal processing
- Audio feedback system
- Modular and scalable code design

## 🚧 Challenges and Solutions
- Sustain sound issue → Frequency reset logic
- Repeated scoring issue → Wait function implementation
- Wiring instability → Breadboard integration and soldering
- Structural instability → Elastic return mechanism redesign

## 🚀 Future Improvements
- Adjustable tempo control using variable resistor
- Melody recording and replay function
- LED-based score visualization
- Full octave expansion with black keys

## 📷 Demonstration
(Insert project images here)

## 📂 Project Structure
- /Arduino_Code
- /LabVIEW_Files
- /Documentation
- /Images
