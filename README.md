# Voice Assistant with OpenAI GPT-4o-mini

## Overview
This project is a voice assistant that takes voice commands, converts them to text, and responds using OpenAI's GPT-4o-mini model. The assistant can:
- Recognize voice commands using `speech_recognition`
- Convert text responses to speech using `pyttsx3`
- Open websites like YouTube and Google

## Features
- **Speech Recognition**: Uses `speech_recognition` to capture voice commands.
- **AI-Powered Responses**: Utilizes OpenAI's `GPT-4o-mini` model to generate intelligent responses.
- **Text-to-Speech**: Converts AI-generated responses into speech using `pyttsx3`.
- **Web Navigation**: Opens YouTube and Google via voice commands.

## Installation
### Prerequisites
Ensure you have Python installed (Python 3.7 or higher recommended).

### Install Required Packages
Run the following command to install the dependencies:
```sh
pip install openai speechrecognition pyttsx3 pyaudio
```
> Note: If you encounter issues installing `pyaudio`, see the Troubleshooting section below.

## Setup
1. **OpenAI API Key**
   - Store your OpenAI API key in a separate file named `apikey.py` with the following content:
     ```python
     api_data = "your_openai_api_key_here"
     ```

2. **Run the Assistant**
   Execute the script using:
   ```sh
   python app.py
   ```

## Usage
1. The assistant will greet you with "Hello, how are you?".
2. Speak into the microphone when prompted with "Listening...".
3. The assistant will process your command and provide a response.
4. If a specific command like "Open YouTube" or "Open Google" is spoken, the corresponding website will open.
5. Say "bye" to exit the program.

## Troubleshooting
### `pyaudio` Installation Issues
If `pyaudio` fails to install, try one of these methods:
1. Install the file [PyAudio-0.2.11-cp36-cp36m-win_amd64.whl]
2. Use the following command for Windows:
   ```sh
   pip install PyAudio-0.2.11-cp310-cp310-win_amd64.whl
   ```

## Future Enhancements
- Support for additional voice commands.
- Integration with other AI models for advanced responses.
- More web navigation features.

## Author
Developed by **Srimythili S P**

