# 🎙️ Speech-to-Speech Translator using Python

This project is a **voice-based translator** that lets users **speak in one language**, translates it into another, and then **plays back the translated speech** — just like a real-time interpreter!

## 🔧 Features
- 🎤 Converts **spoken input** into text using `speech_recognition`
- 🌍 Translates the recognized text using `googletrans`
- 🔊 Converts translated text back into **spoken audio** using `gTTS`
- 💾 Plays the audio by saving it as a temporary `.mp3` file
- 🕐 Allows setting a time limit for recording input

## 🛠️ Libraries Used
- `speech_recognition`: For capturing audio and converting it to text
- `googletrans==4.0.0-rc1`: For translating text between languages
- `gTTS`: Google Text-to-Speech to generate audio from text
- `os`, `time`: File handling and unique filename generation

## 🧠 How It Works
1. You speak into the mic (e.g., in Telugu)
2. It converts your speech to text
3. You choose the target language (e.g., Hindi)
4. It translates the text and reads it aloud in the selected language
