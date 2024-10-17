# Secure CAPTCHA Verification System

This project implements a secure CAPTCHA verification system using Flask, Python, and Google Text-to-Speech (gTTS) for both visual and audio CAPTCHA challenges. Users are asked to solve a CAPTCHA in a limited amount of time, either by typing the characters shown in the image or by listening to an audio CAPTCHA.

## Features

- **Image CAPTCHA**: A randomly generated alphanumeric code displayed in an image.
- **Audio CAPTCHA**: The same alphanumeric code read aloud using Google Text-to-Speech (gTTS).
- **Timed Verification**: Users must enter the CAPTCHA within 30 seconds to be validated.
- **Responsive Design**: The web interface is mobile-friendly and works across different devices.
- **Feedback**: Users receive real-time feedback whether they entered the CAPTCHA correctly or incorrectly.

## Technologies Used

- **Flask**: A micro web framework for building the web server.
- **gTTS (Google Text-to-Speech)**: Converts text CAPTCHA to audio.
- **captcha**: Generates image CAPTCHA.
- **HTML, CSS, JavaScript**: For the frontend design and timer functionality.
- **Python**: For backend logic and CAPTCHA generation.

