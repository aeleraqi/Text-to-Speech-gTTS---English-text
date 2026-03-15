# English Text-to-Speech with gTTS 🔊

[![Language](https://img.shields.io/badge/Language-Python%20%7C%20Jupyter-blue)](https://github.com/aeleraqi/Text-to-Speech-gTTS---English-text)
[![Stars](https://img.shields.io/github/stars/aeleraqi/Text-to-Speech-gTTS---English-text?style=social)](https://github.com/aeleraqi/Text-to-Speech-gTTS---English-text/stargazers)

Convert **English text** to natural-sounding speech using Google's Text-to-Speech (gTTS) API.

## 📖 About

A simple, easy-to-use Python library for converting English text into high-quality MP3 audio using Google's TTS engine. Perfect for accessibility tools, educational apps, podcast automation, and voice-over generation.

## ✨ Features

- Convert any English text to MP3 audio
- Multiple accent options (US, UK, Australian, etc.)
- Adjustable speech speed
- IPython audio playback in Jupyter

## 🚀 Getting Started

```bash
pip install gtts
```

## 💡 Usage

```python
from gtts import gTTS
from IPython.display import Audio

tts = gTTS(text="Welcome to the world of text-to-speech!", lang='en', tld='us')
tts.save("output.mp3")
Audio("output.mp3")
```

---
**Author:** [Amr Eleraqi](https://github.com/aeleraqi) — Data Analyst | NLP Specialist | Machine Learning Expert | Educator  
**Affiliation:** Toronto Metropolitan University, Ontario, Canada  
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0935--0026-brightgreen)](https://orcid.org/0000-0003-0935-0026) [![GitHub](https://img.shields.io/github/followers/aeleraqi?label=Follow&style=social)](https://github.com/aeleraqi)
