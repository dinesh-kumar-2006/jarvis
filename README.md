JARVIS Voice Assistant
A simple, customizable voice assistant built with Python. JARVIS listens for your commands and can greet you, open websites, play music, tell the time, and search Wikipedia.

Features
Personalized Greeting: Greets you based on the time of day.

Voice Commands: Accepts spoken instructions using your microphone.

Website Access: Opens YouTube, Google, and Stack Overflow with voice commands.

Music Playback: Plays your favorite music from a specified directory.

Time Announcement: Tells you the current time.

Wikipedia Search: Fetches and reads Wikipedia summaries for your queries.

Requirements
Python 3.x

pyttsx3 (for text-to-speech)

speech_recognition (for voice recognition)

wikipedia (for fetching Wikipedia summaries)

webbrowser (for opening web pages; included in Python standard library)

os (for music directory management; included in Python standard library)

datetime (for time functions; included in Python standard library)

Installation
Clone the repository:

bash
git clone https://github.com/yourusername/jarvis-voice-assistant.git
cd jarvis-voice-assistant
Install required packages:

bash
pip install pyttsx3 SpeechRecognition wikipedia
Run the assistant:

bash
python jarvis.py
Usage
Start the script:
python jarvis.py

Speak your command:

"Open YouTube"

"Open Google"

"Open Stack Overflow"

"Play music" (make sure to update the music directory path in the code)

"What is the time"

"Wikipedia [your query]"

Customization
Change the music directory:
Modify the music_dir variable in the code to point to your music folder.

Voice settings:
Adjust the voice or language by changing the engine.setProperty('voice', voices.id) line.
