# Final Project — Emotion Detection Web Application

An AI-powered web application that detects emotions in text using the IBM Watson NLP library and Flask.

## Overview

This Final Project takes text input from a user, analyzes the emotion conveyed (anger, disgust, fear, joy, sadness), and returns the emotion scores along with the dominant emotion.

## Project Structure

* `EmotionDetection/`: Python package containing emotion detection logic.

  * `__init__.py`: Package initializer.
  * `emotion_detection.py`: Contains `emotion_detector` interacting with the Watson NLP EmotionPredict service.
* `server.py`: Flask web server providing the application routes.
* `templates/index.html`: Web interface for user interaction.
* `static/mywebscript.js`: Client-side JavaScript handling API requests.
* `test_emotion_detection.py`: Unit tests verifying emotion detection accuracy.
* `evidence/`: Submission artifacts and verification logs.

## Setup and Running

1. Install dependencies:

```bash
pip install flask requests pylint
```

2. Run unit tests:

```bash
python -m unittest test_emotion_detection.py
```

3. Start the Flask application:

```bash
python server.py
```

4. Access the web interface at:

`http://127.0.0.1:5000`

## Project Name

**Final Project — Emotion Detection Web Application**
