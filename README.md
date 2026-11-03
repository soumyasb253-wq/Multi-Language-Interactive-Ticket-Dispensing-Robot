# Multi-Language Interactive Ticket Dispensing Robot

## Project Overview
The Multi-Language Interactive Ticket Dispensing Robot is a voice-controlled automated ticket booking system developed using Raspberry Pi and Python. It enables users to book tickets through voice commands in multiple languages, making the ticketing process simple, accessible and user-friendly.

The system supports English, Hindi, Kannada and Marathi. It uses speech recognition, text-to-speech, QR code generation and thermal printing to automate the ticket booking process.

## Objectives
- To develop a voice-based automated ticket booking system.
- To support multiple regional languages.
- To reduce manual effort in ticket booking.
- To provide a touch-free ticket booking experience.
- To improve accessibility for users with different language backgrounds.
- To automate QR code generation and ticket printing.

## Hardware Requirements
- Raspberry Pi
- USB Microphone
- Speaker
- Thermal Printer
- 3.5-inch LCD/TFT Display
- Power Supply
- MicroSD Card
- Connecting Wires and PCB

## Software Requirements
- Python 3
- Raspberry Pi OS
- SpeechRecognition
- Google Text-to-Speech (gTTS)
- Google Speech-to-Text
- Tkinter
- Pygame
- MQTT
- QR Code Library
- Pillow (PIL)

## Working Principle
1. The system activates when it recognizes the wake word "Hello Ticket".
2. The user selects a preferred language.
3. The microphone captures the user's voice commands.
4. Speech recognition converts voice into text.
5. The user provides the destination and ticket quantity.
6. The system calculates the total ticket fare.
7. A QR code is generated for the payment process.
8. Payment confirmation is simulated using a demo application and MQTT communication.
9. After successful confirmation, the thermal printer prints the ticket.

## Supported Languages
- English
- Hindi
- Kannada
- Marathi

## Applications
- Bus Stations
- Railway Stations
- Metro Stations
- Smart Ticketing Kiosks
- Event Ticketing Systems
- Public Transportation Services

## Advantages
- Supports multiple languages.
- Provides voice-based interaction.
- Reduces manual ticket booking.
- Improves accessibility.
- Offers touch-free operation.
- Reduces dependency on ticket counters.

## Limitations
- Requires an internet connection for online speech recognition services.
- Background noise may affect voice recognition accuracy.
- The payment process in this project uses a demonstration application rather than a live payment gateway.

## Learning Outcomes
- Raspberry Pi programming.
- Python application development.
- Speech recognition and text-to-speech integration.
- Multilingual voice processing.
- MQTT communication.
- QR code generation.
- Hardware and software integration.

## Project Documentation
The complete academic project report is available in this repository as a PDF document.

## Project Domain
Robotics and Automation | Embedded Systems | Python | IoT
