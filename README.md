# VisionChat
📸🤖 Image to Text QA: Extract questions from any image and get instant answers using OpenAI GPT. Unleash the power of OCR and AI on your images and dive into a world of knowledge! 🌟💬

# Image to Text Question Answering

This project uses OCR (Optical Character Recognition) to extract text from images, identifies any questions in the text, and fetches the answers using the OpenAI GPT model.

## Prerequisites

- Python
- OpenAI API Key
- Tesseract

### Libraries Used

- OpenCV (cv2)
- pytesseract
- NLTK
- openai
- regex (re)
- os

### Licenses

- OpenCV: BSD license
- pytesseract: Apache License 2.0
- NLTK: Apache License 2.0
- openai: MIT License
- regex: Python Software Foundation License

### Tesseract

This project utilizes Tesseract for OCR. Please ensure that Tesseract is installed and the path to the Tesseract binary is correctly specified in the script.

### OpenAI API Key

You need to have an OpenAI API key and set it as an environment variable before running the script.

#### MacOS/Linux
```sh
export OPENAI_API_KEY="your_api_key"

#### Windows
```sh
set OPENAI_API_KEY="your_api_key"

####Powershell
```sh
$env:OPENAI_API_KEY="your_api_key"
