# Text_Emotion_Recognition
## Problem
In this digital age, vast amount of textual data are generated daily through various online platforms. Understanding the emotions conveyed in textual content is crucial for various applications. Text Emotion Recognition (TER) is a NLP task that involves identifying and classifying emotions such as happiness, sadness, anger, fear, and surprise from textual data. Unlike traditional sentiment analysis, which classifies text into positive/negative/neutral sentiments, TER provides a more fine-grained emotional understanding. This project aims to develop a Text Emotion Recognition system using advanced NLP techniques, including deep learning models with the most relevant features without having any missing values, duplicate data, imbalance and noisy data to improve the performance of model, so that the model can accurately recognize emotions expressed in textual data.
## Dataset Information
- Dataset Used: MELD (Multimodal EmotionLines Dataset) derived from dialogues in the TV series Friends.
- Utterance: The spoken text/dialogue
- Speaker: Character who spoke the utterance
- Emotion: Emotion label (e.g., neutral, surprise, joy, sadness, etc.)
- Sentiment: Sentiment label (positive, neutral, negative)
- Dialogue_ID: Unique identifier for the dialogue
- Utterance_ID: Sequence number of the utterance in the dialogue
- Season and Episode: Location of the utterance in the TV series
- StartTime, EndTime: Timestamps for the utterance
## Approach Used
- Augmented training data using EDA (Easy Data Augmentation) techniques to improve model generalization.
- Performed text preprocessing: cleaning, tokenization, lemmatization, and stopword removal.
- Handled class imbalance using RandomOverSampler.
- Used GloVe embeddings (200D) to convert text into numerical vectors.
- Trained and evaluated deep learning models including RNN, LSTM, BiLSTM (Bidirectional LSTM), and GRU model to capture emotions.
- Evaluated model using accuracy, precision, recall, and F1-score, with a focus on accuracy and recall to effectively detect emotions.
## Impact
- Enables emotion-aware applications in areas like customer support, education, and healthcare.
- Enhances natural language understanding in chatbots and virtual assistants by incorporating emotional intelligence.
- Supports the development of emotionally adaptive systems that respond to users more empathetically.
