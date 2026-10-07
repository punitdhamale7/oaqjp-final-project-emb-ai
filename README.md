# Final Project: AI-Based Web Application Development and Deployment

## Project Name: Final Project - Emotion Detection Application

A web-based AI application that detects emotions in customer and user feedback text using the IBM Watson NLP library and Flask.

## Project Overview
This is the Final Project for AI-Based Web Application Development and Deployment. The project analyzes text statements to detect the emotions conveyed—such as **anger**, **disgust**, **fear**, **joy**, and **sadness**—and identifies the **dominant emotion**. It is built using Python, packaged modularly as `EmotionDetection`, and deployed as a web application using Flask.

## Repository Structure
```
.
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── test_emotion_detection.py
├── server.py
└── README.md
```

## Features
- **Emotion Detection Package**: Modular Python package utilizing IBM Watson NLP Emotion Predict model.
- **Output Formatting**: Processes responses and extracts emotion scores and the dominant emotion.
- **Unit Testing**: Automated unit tests using Python's `unittest` framework to ensure high prediction accuracy.
- **Web Interface**: Interactive web interface built with HTML, Bootstrap, and JavaScript.
- **Error Handling**: Graceful error handling for blank inputs and invalid queries (HTTP status code 400).
- **Clean Code**: Adheres to PEP 8 standards with a perfect 10/10 Pylint score.

## Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/punitdhamale7/oaqjp-final-project-emb-ai.git
   cd oaqjp-final-project-emb-ai
   ```

2. **Install required packages**:
   ```bash
   pip install flask requests pylint
   ```

3. **Run Unit Tests**:
   ```bash
   python test_emotion_detection.py
   ```

4. **Run Static Code Analysis**:
   ```bash
   pylint server.py
   ```

5. **Run the Flask Application**:
   ```bash
   python server.py
   ```
   Open your browser and navigate to `http://localhost:5000` or `http://127.0.0.1:5000`.

## Author
Punit Dhamale - [GitHub](https://github.com/punitdhamale7)