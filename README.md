# AI-Based Voice Assistant - Alisa

This Python project is an AI-based voice assistant named Alisa. It can perform various tasks such as opening websites, sending emails, playing music, and more, based on voice commands. The project utilizes libraries like `pyttsx3` for text-to-speech conversion, `speech_recognition` for speech-to-text, `wikipedia` for fetching information, and `smtplib` for sending emails.

## Features

- **Voice Interaction**: Alisa can interact with users using voice commands.
- **Wikipedia Search**: Fetches and reads summaries from Wikipedia.
- **Web Browsing**: Opens popular websites like YouTube, Google, StackOverflow, and ICICI Bank.
- **Email Functionality**: Sends emails via voice command.
- **Music Playback**: Plays music from a specified directory.
- **Time Reporting**: Tells the current time.
- **Application Launching**: Opens applications like VS Code and PowerPoint.

## Prerequisites

Before running the script, ensure you have the following Python libraries installed:

- `pyttsx3`
- `speech_recognition`
- `wikipedia`
- `webbrowser` (part of the standard library)
- `os` (part of the standard library)
- `smtplib` (part of the standard library)
- `datetime` (part of the standard library)

You can install any missing libraries using pip:

```bash
pip install pyttsx3 speechrecognition wikipedia
