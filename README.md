# MyAlexa_assistant


***Technologies and Libraries Used***

* Python 3

* speech_recognition

* pyttsx3

* pywhatkit

* wikipedia

* pyjokes

* datetime

***Project Structure***

alexa-voice-assistant/

│

├── myalexa.py

├── README.md

***Prerequisites***

* Python Installation

    Ensure Python 3.8 or above is installed.

* Check version by using the following command :

    " python --version "

* Microphone and Internet :

    * A working microphone is required

    * Internet connection is required for Google Speech Recognition, Wikipedia, and YouTube

***Installation Steps***

**Step 1**:
Clone the Repository
git clone https://github.com/your-username/alexa-voice-assistant.git
cd alexa-voice-assistant

**Step 2**:
Install Required Libraries
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes

**Step 3**: Install PyAudio

Windows
pip install pipwin
pipwin install pyaudio

Linux
sudo apt-get install portaudio19-dev python3-pyaudio
pip install pyaudio

macOS
brew install portaudio
pip install pyaudio

**How to Run the Assistant**

python myalexa.py


After starting, the assistant will prompt you to speak using the wake word "Alexa".

***What exactly this assistant capable of doing***

It does what you command in the follwing manner

| Command Example              | Action                |
| ---------------------------- | --------------------- |
| Alexa play Believer          | Plays song on YouTube |
| Alexa what is the time       | Tells current time    |
| Alexa who is APJ Abdul Kalam | Gives Wikipedia summary     |
| Alexa tell me a joke         | Tells a joke          |
| Alexa are you single         | Conversational reply  |
| Alexa date                   | Conversational reply  |
