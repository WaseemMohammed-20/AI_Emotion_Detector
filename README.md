# Multilingual AI Emotion Detection

A **multilingual AI-based Emotion Detection system** that supports **English, Hindi, and Telugu**. The system detects the input language, translates non-English text into English, and predicts the underlying emotion using Machine Learning. Real-time predictions include both the **emotion** and **confidence score**.

## Features
- Supports **English, Hindi, and Telugu** inputs
- **Automatic language detection** and translation
- Uses **TF-IDF vectorization** with a supervised ML classifier
- Returns **emotion + confidence score** in real-time
- Ideal for applications like mental health monitoring, sentiment analysis, customer feedback, and human-computer interaction

## Technology Stack
- **Python** – Core programming
- **scikit-learn** – Machine Learning (classifier & TF-IDF)
- **NLTK / spaCy** – Text preprocessing
- **langdetect** – Language detection
- **Google Translate API** – Translation
- **Flask / Streamlit** – Real-time web interface

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/multilingual-emotion-detection.git
Navigate to the project directory : 
cd multilingual-emotion-detection

Install dependencies
pip install -r requirements.txt

Run the web app
streamlit run app.py
Enter text in English, Hindi, or Telugu

Get the predicted emotion with a confidence score
Example
Input Text (Language)	Predicted Emotion	Confidence
"I am so happy today!" (English)	Happy	0.92
"నాకు నచ్చింది" (Telugu)	Joy	0.88
"मैं उदास हूँ" (Hindi)	Sad	0.90
Contributions are welcome! Please create an issue or submit a pull request for improvements, bug fixes, or new features.
