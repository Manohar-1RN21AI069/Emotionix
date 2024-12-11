Emotionix 🎭
Emotionix is an emotion detection system designed to identify and analyze emotions using text, voice, and facial expressions. Built with a Dash-based web interface, it provides a seamless user experience to detect emotions, interact with a chatbot, and receive personalized recommendations for improving emotional well-being.

🛠 Features

Emotion Detection:
Text-Based Emotion Detection: Analyze the emotional content of user-provided text input.
Voice-Based Emotion Detection: Detect emotions from recorded voice samples.
Facial Emotion Detection: Analyze real-time video feeds to determine facial expressions and emotions.

Interactive Chatbot:
A conversational AI chatbot provides insights, motivational messages, and emotional support.

Personalized Recommendations:
AI-driven content suggestions tailored to the detected emotion.
Spotify integration for music recommendations.

User-Friendly Dash Web Interface:
Built with Dash and styled using Dash Bootstrap Components for an elegant and responsive design.

📁 Project Structure

EMOTIONIX/
├── data/                     # Data-related resources
│   ├── audio/                # Audio files for training/analysis
│   └── dataset/              # Dataset files
├── src/                      # Source code directory
│   ├── __pycache__/          # Compiled Python files (ignore or clean)
│   ├── voice_detection/      # Voice detection module
│   │   └── model/            # Submodule for voice model-related scripts
│   │       ├── dataset_download.py # Script to download datasets
│   │       └── train_model.py      # Script to train models
│   ├── chatbot.py            # Chatbot implementation
│   ├── face_detection.py     # Facial emotion detection logic
│   ├── feedback.py           # Feedback generation module
│   ├── recommend.py          # Recommendation system logic
│   ├── text_detection.py     # Text emotion detection logic
│   └── voice_detection.py    # Voice emotion detection logic
├── .cache/                   # Cache files (temporary)
├── app.py                    # Main Dash web application
└── main.py                   # Entry point for running the project

🚀 How to Run the Project

Clone the Repository:
git clone https://github.com/Manohar-1RN21AI069/emotionix.git
cd EMOTIONIX

Install Dependencies:
Install Python dependencies:
pip install -r requirements.txt

Run the Application:
Start the Dash application:
python app.py
Open your browser and navigate to http://127.0.0.1:8050.

🧰 Technologies Used
Backend
Python: Core programming language.
Dash: Framework for building web applications.
Dash Bootstrap Components: For modern, responsive UI components.
Machine Learning Libraries:
transformers: Text-based sentiment analysis.
DeepFace: Facial emotion detection.
Librosa: Audio feature extraction.
scikit-learn: Voice emotion detection.

Frontend
Dash: Web-based frontend framework.
HTML/CSS: Styled with custom and Bootstrap-based styles.

APIs
Spotify API: For music recommendations.
Google Generative AI: For chatbot and feedback generation.

💡 How It Works

Emotion Detection:
Text: Enter text to analyze sentiment and detect emotions.
Voice: Record and analyze audio for emotional tone.
Video: Analyze facial expressions in real-time via webcam.

Recommendations:
AI Recommendations: Emotion-based feedback and suggestions.
Spotify: Curated playlists for mood improvement.
Interactive Chatbot:
Chat with a generative AI-based bot to get emotional support and motivational advice.
Web Interface:

Navigate between features via a sidebar. The semi-transparent design ensures a modern and clean look.

🎉 Contributions
Contributions are welcome! Feel free to fork the repository, create an issue, or submit a pull request.
