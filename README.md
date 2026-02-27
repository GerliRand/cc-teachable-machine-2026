# Teachable Machine Audio – GO/STOP Demo

This project is part of the **Cloud Computing** course assignment - Module 3 task 1/2.
It builds upon the Teachable Machine model created earlier in Module 1.

In Module 1, an audio classification model was trained using Google Teachable Machine with three sound classes:
- Go
- Stop
- Background Noise

## Project Description

This application performs real-time voice command recognition directly in the browser.

When the user clicks Start listening, the application:
1. Loads the Teachable Machine model files
(model.json, metadata.json, weights.bin)

2. Requests microphone permission

3. Begins real-time audio classification

4. Displays predictions and system state updates

**Scores (Debug Window)**
he Scores section displays real-time probability values for each class:
- Background Noise
- Go
- Stop

This allows verification of how the model interprets incoming audio.

**Log Window**
The Log section records:
- When listening starts or stops
- Detected commands and their confidence scores
- Background noise events (limited to avoid spam)
- State transitions (RUNNING / STOPPED)

## Technologies
- HTML
- JavaScript
- Google Teachable Machine 

## How to Run the Project

1) Clone or download the repository
2) Open the project folder
3) Open go-stop.html in a web browser
4) Allow microphone access when prompted