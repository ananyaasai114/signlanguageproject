# team-name
# Real-Time Voice to Sign Language

This project converts spoken words into sign language videos in real-time, using a web-based interface. The app listens to a user's speech, transcribes it into text, and displays a corresponding sign language video for recognized phrases.

## Features
- **Real-Time Speech Recognition**: Uses browser's speech recognition capabilities to transcribe spoken words.
- **Sign Language Video Mapping**: Matches recognized words to corresponding sign language videos.
- **Interactive Interface**: Allows users to start and stop voice recognition easily with buttons.
- **Fallback Handling**: Displays an appropriate message if no sign language video is found.

## Prerequisites
- **Google Chrome**: The project uses `webkitSpeechRecognition`, which is supported in Chrome.
- **Web Server**: A simple HTTP server is needed to run the app (e.g., Python’s built-in HTTP server).

## Getting Started
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/real-time-voice-to-sign-language.git
   cd real-time-voice-to-sign-language
   ```
