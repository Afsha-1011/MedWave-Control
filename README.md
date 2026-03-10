# MedWave Control

MedWave Control is a touchless interaction system that allows medical professionals to control digital interfaces using hand gestures and voice commands. 
This helps maintain sterile environments in hospitals by reducing the need to touch keyboards or screens.

## Problem
In healthcare environments, especially during surgeries:
- Doctors cannot touch keyboards or devices
- Touching surfaces can break sterile conditions
- It slows down access to patient data and medical images

## Solution
This project enables doctors to control systems without physical contact using:
- Hand gestures
- Voice commands

## How It Works
1. The camera captures hand movements.
2. MediaPipe detects hand landmarks.
3. Gestures are recognized and mapped to actions.
4. Voice commands provide an additional control method.
5. The system simulates actions like scrolling, selecting, or zooming.

## Features
- Touchless gesture control
- Voice command support
- Real-time hand tracking
- Control of system functions like scrolling, navigation, and zoom

## Tech Stack
- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- Speech Recognition

## Use Cases
- Operating rooms
- Medical imaging navigation
- Sterile healthcare environments

## Future Improvements
- More gesture types
- AI-based gesture recognition
- Integration with hospital software systems
