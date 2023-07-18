# Desktop Voice Assistant - Jarvis

A voice assistant program that interacts with the user through speech recognition and text-to-speech conversion. It can perform various tasks such as searching on Wikipedia, opening websites, playing music, retrieving the current time, and sending emails.

## Prerequisites

- Python 3.x
- Install required packages using `pip`:
**pip install pyttsx3** speechRecognition wikipedia pyaudio

  
## Usage

1. Run the `main.py` script.
2. The assistant will greet you according to the time of the day and ask how it can assist you.
3. You can give voice commands to perform various tasks.

## Features

- Wikipedia search: Say "Wikipedia" followed by your query to search and retrieve information from Wikipedia.
- Open websites: Say "Open YouTube", "Open Google", or "Open Stack Overflow" to open the respective websites.
- Play music: Say "Play music" to play music from a specified directory.
- Retrieve current time: Say "What is the time?" or "Tell me the time" to get the current time.
- Open code editor: Say "Open code" to open a code editor (default path is provided as an example).
- Send email: Say "Email to [recipient]" to send an email (requires email credentials and recipient's email address).

## Configuration

- Email configuration: Provide your email address and password in the `sendEmail()` function to enable sending emails.

## Notes

- Ensure that you have a working microphone for voice input.
- Modify the code as per your system paths and requirements.

## License

This project is licensed under the [[MIT License](LICENSE).](https://opensource.org/license/mit/)https://opensource.org/license/mit/

