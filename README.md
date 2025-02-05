
ESP32 Voice Assistant 🎙

Using MAX9814 Microphone & I2S Amplifier

Overview

This project is a voice assistant powered by ESP32 that:
✅ Records audio using the MAX9814 microphone
✅ Converts speech to text using Deepgram STT API
✅ Sends the text to Gemini AI for generating answers
✅ Uses Google TTS or OpenAI Whisper TTS to convert text to speech
✅ Plays the response through an I2S amplifier and speaker


---

Features 🚀

Wake word detection using Porcupine 🦜

RGB LED indicators for different modes 🔴🟢🔵

Offline & Online AI processing via Gemini API

SD card storage for temporary audio files

Real-time voice interaction with a web-based UI



---

Hardware Requirements 🛠

1️⃣ ESP32 Development Board

Model: ESP32-D0WD-V3


2️⃣ Audio Components

Microphone: MAX9814 (Analog) or INMP441 (I2S)

Amplifier: MAX98357 (I2S)

Speaker: 3W or 5W, 4Ω


3️⃣ Storage & Connectivity

SD Card Module (FAT32 formatted)

2.4 GHz Wi-Fi for cloud-based AI processing


4️⃣ Additional Components

Push Button (to start/stop recording)

RGB LED (for status indicators)



---

Software Requirements 💻

Arduino Libraries

✅ ArduinoJson
✅ ESPAsyncWebServer
✅ SD
✅ I2S
✅ WiFi

APIs Used

✅ Deepgram API (for speech-to-text)
✅ Gemini AI (for answering questions)
✅ Google TTS / OpenAI Whisper (for text-to-speech)


---

How It Works ⚙️

1️⃣ Press the button to start recording
2️⃣ Speak your question into the MAX9814 microphone
3️⃣ The ESP32 uploads audio to Deepgram STT and gets text
4️⃣ The text is sent to Gemini AI, which generates an answer
5️⃣ The answer is converted into speech using Google TTS / Whisper TTS
6️⃣ The response is played via the MAX98357 I2S amplifier and speaker


---

Setup Instructions 🛠

1️⃣ Install Required Libraries in Arduino IDE
2️⃣ Connect the hardware as per wiring diagram
3️⃣ Configure Wi-Fi credentials in the ESP32 code
4️⃣ Get API Keys for Deepgram, Gemini, and Google TTS (optional)
5️⃣ Upload the sketch to ESP32
6️⃣ Press the button and start interacting! 🎙


---

Future Enhancements 🔥

Add Edge AI Wake Word Detection

Improve Response Speed & Accuracy

Support Offline Speech Recognition



---

License 📜

This project is open-source under the MIT License.


---

🚀🔥
