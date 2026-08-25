# Image-Speech Recognition System for Impaired Users

An assistive AI system designed to enhance accessibility for visually and hearing-impaired individuals. This project integrates image recognition and speech processing to interpret surroundings and provide meaningful audio or visual feedback 3.

## Features

- 🔉 Converts detected objects/scenes in images into descriptive speech (for visually impaired users)
- 🖼️ Translates speech commands into relevant images or actions (for hearing-impaired users)
- 📷 Real-time image processing using pre-trained CNN models
- 🗣️ Speech recognition and text-to-speech using open-source tools
- 🛠️ Simple and intuitive user interface for easy interaction

## Technologies Used

- **Language:** Python
- **Computer Vision:** OpenCV
- **Deep Learning:** TensorFlow / PyTorch
- **Speech Processing:** SpeechRecognition, gTTS, pyttsx3
- **Interface:** Streamlit / Tkinter

## How It Works

1. **Image Input** – The system captures or receives an image, which is processed using a pre-trained CNN model to detect objects and scenes.
2. **Image-to-Speech** – Detected content is converted into a natural-language description and read aloud using text-to-speech, helping visually impaired users understand their surroundings.
3. **Speech-to-Image** – Spoken commands are captured via speech recognition and mapped to relevant images or actions, helping hearing-impaired users interact visually.
4. **User Interface** – A lightweight GUI (Streamlit or Tkinter) ties the workflow together for easy, real-time interaction.

## Installation

```bash
git clone <repository-url>
cd image-speech-recognition-system
pip install -r requirements.txt
```

## Usage

```bash
python app.py
```

Or, if using Streamlit:

```bash
streamlit run app.py
```

## Goal

To build an inclusive AI system that empowers impaired users by bridging the communication gap between visual and auditory information — making everyday surroundings and communication more accessible for everyone.

