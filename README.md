# GameGuardian: Toxicity Recognition from Chat

## Overview

Welcome to GameGuardian, a powerful tool designed to recognize toxicity in player chat data. This project utilizes advanced Natural Language Processing (NLP) techniques and Deep Learning algorithms, including Logistic Regression, Support Vector Machines (SVM), and Long Short-Term Memory (LSTM) networks. By harnessing the capabilities of these cutting-edge technologies, GameGuardian achieves an impressive accuracy rate of 87% in sentiment classification, effectively identifying and flagging toxic messages within gaming communities.

## Features

- **Toxicity Detection**: GameGuardian employs state-of-the-art NLP models to analyze and classify player chat data, distinguishing between toxic and non-toxic messages.
- **Multi-Emotion Recognition**: In addition to detecting toxicity, GameGuardian can identify a range of human emotions, including Joy, Fear, Anger, Love, Sadness, and Surprise, enhancing the understanding of player sentiment.
- **Streamlit Web Application**: The project is packaged as a user-friendly Streamlit web application, making it easy to interact with and deploy for real-time toxicity monitoring.

## Getting Started

To utilize GameGuardian and deploy the toxicity recognition system in your gaming platform, follow these simple steps:

1. **Clone the Repository**: Begin by cloning this GitHub repository to your local machine.

    ```bash
    git clone https://github.com/ArjunT254/Toxicity-Detection
    ```

2. **Install Dependencies**: Navigate to the project directory and install the required dependencies.

    ```bash
    cd GameGuardian
    pip install -r requirements.txt
    ```

3. **Run the Web Application**: Launch the Streamlit web application to start detecting toxicity in player chat data.

    ```bash
    streamlit run app.py
    ```
    
    The app uses the following saved files:
    logistic_regresion.pkl: Pickle file containing the logistic regression model.
    tfidf_vectorizer.pkl: Pickle file containing the TF-IDF vectorizer.
    label_encoder.pkl: Pickle file containing the label encoder.

4. **Interact with the App**: Open your web browser and access the provided URL to interact with GameGuardian. Enter sample chat messages or connect it to your gaming platform for real-time monitoring.

## Contributing

Contributions to GameGuardian are welcome! Whether you want to add new features, improve the existing codebase, or fix bugs, feel free to submit pull requests. For major changes, please open an issue first to discuss the proposed updates.

## License

This project is licensed under the MIT License. Feel free to modify and distribute it for commercial or non-commercial purposes. See the `LICENSE` file for more information.

## Acknowledgments

Special thanks to the contributors and open-source projects that made GameGuardian possible. Your efforts are greatly appreciated in advancing the field of toxicity recognition and fostering positive gaming communities.
