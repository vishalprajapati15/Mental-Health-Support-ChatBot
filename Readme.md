# Mental Health Support ChatBot 🤖💙

![Mental Health Support](./Mental%20Health%20Support%20ChatBot.png)

A compassionate AI assistant that provides mental health support by analyzing user emotions, generating empathetic responses using Google's Gemini API, and offering audio feedback via text-to-speech.

## Features ✨

- **Sentiment Analysis**: Detects positive/negative/neutral sentiment using TextBlob
- **Emotion Recognition**: Identifies 7 emotions (anger, joy, sadness, etc.) using Hugging Face models
- **AI-Powered Responses**: Generates compassionate responses using Gemini 1.5 Flash
- **Text-to-Speech**: Converts AI responses to audio using gTTS (Google Text-to-Speech)
- **Data Visualization**: Creates pie charts for sentiment and emotion distributions
- **Rate Limit Handling**: Automatic retries for API rate limiting (429 errors)

## Tech Stack 🛠️

| Component | Technology |
|-----------|------------|
| **AI Models** | Gemini 1.5 Flash, DistilRoBERTa |
| **NLP Libraries** | TextBlob, Transformers |
| **Text-to-Speech** | gTTS (Google Text-to-Speech) |
| **Visualization** | Matplotlib |
| **API Handling** | Google Generative AI SDK |

## Installation 📦

```bash
# Install required packages
!pip install -q google-generativeai
!pip install textblob 
!pip install transformers torch
!pip install gTTS  # Text-to-speech functionality
!pip install playsound  # Audio playback

# Download TextBlob corpora
!python -m textblob.download_corpora