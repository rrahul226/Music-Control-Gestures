# Music-Control-Gestures

📌 Overview
The Gesture-Controlled Music Arpeggiator is an interactive web application that transforms your hand gestures into live music.
Using computer vision and real-time audio synthesis, it detects your hand position, finger movements, and gestures to control pitch, volume, and drum beats — all without touching a physical instrument.

🎯 How It Works
Webcam Hand Tracking
Uses MediaPipe Hands to detect hand landmarks in real-time.
Tracks 21 key points per hand, including fingertips and palm center.

Pitch Control
Pitch changes depending on the horizontal position of the fingers.
Example: Moving fingers left → lower pitch; right → higher pitch.

Volume Control
The vertical position of the hand adjusts volume dynamically.
Higher hand position = louder sound.
Drum Beats Trigger
Specific fingers aligned to on-screen zones trigger kick, snare, hihat, and clap sounds.
Each zone is mapped to a particular drum instrument.

Waveform Visualizer
Displays live audio waveforms that respond to pitch and volume changes.

🌟 Features
Touchless music generation using hand gestures.
Real-time pitch, volume, and drum control.
Visual feedback through an on-screen waveform.
Fully browser-based — no extra software required.
Works on desktop with any standard webcam.


Demo Video link : https://drive.google.com/file/d/1JV85RAh4OTuD3G8sFZ04ME8IWjQRV6Hm/view?usp=sharing

