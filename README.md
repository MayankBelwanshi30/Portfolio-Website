# Hindi Sign Language Recognition System

A comprehensive deep learning-based system for real-time Hindi character recognition using hand gestures. This project combines computer vision, mediapipe hand tracking, and CNN-based classification to create an intuitive interface for typing Hindi characters through hand gestures.

## 🚀 Features

- **Real-time Hand Gesture Recognition**: Uses MediaPipe for robust hand tracking
- **Dual Recognition Modes**: 
  - **Machine Learning Mode**: CNN-based classification for accurate gesture recognition
  - **Rule-based Mode**: Fallback using finger position mapping
- **Hindi Text Display**: Renders Devanagari script with proper font support
- **Text-to-Speech**: Converts typed Hindi text to audio using gTTS
- **Dataset Creation Tool**: Built-in tool for capturing training data
- **Model Training Pipeline**: Complete training workflow with data augmentation

## 📋 Prerequisites

### Python Packages
```bash
pip install torch torchvision opencv-python mediapipe gtts pillow numpy
