# VisionChat
📸🤖 Image to Text QA: Extract questions from any image and get instant answers using VisionChat. Unleash the power of OCR and AI on your images and get things done faster! 🌟💬

# Image to Text Question Answering

This project uses OCR (Optical Character Recognition) to extract text from images, identify any questions in the text, and fetch the answers using the OpenAI GPT model.

## Prerequisites

- Python
- OpenAI API Key
- Tesseract OCR

### Libraries Used

- OpenCV (BSD license)
- pytesseract (Apache License 2.0)
- NLTK (Apache License 2.0)
- openai (MIT License)
- regex (Python Software Foundation License)

### Tesseract

This project utilizes Tesseract for OCR. Please ensure that the Tesseract executable is installed and the path is correctly defined.

### OpenAI API Key

You need to have an OpenAI API key and set it as an environment variable before running the script.

#### Commands

**Linux/MacOS:**
`export OPENAI_API_KEY="your_api_key"`

**Windows:**
`set OPENAI_API_KEY="your_api_key"`

**PowerShell:**
`$env:OPENAI_API_KEY="your_api_key"`
