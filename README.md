
# IMDb Sentiment Analysis Application

This repository contains an **IMDb Sentiment Analysis Application** built using **Streamlit**, **Simple RNN**, and **Word Embeddings**. The application allows users to input text (movie reviews) and predicts the sentiment as **positive** or **negative**.

## Features
- **Interactive UI**: Powered by Streamlit for a simple and user-friendly interface.
- **Text Sentiment Analysis**: Utilizes a trained model to classify reviews into positive or negative sentiment.
- **Deep Learning**: Built with a Simple RNN architecture and word embeddings for efficient text processing and classification.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Ashes-Nanda/IMDb-SentimentPrediction.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run main.py
   ```
4. Open the local server link provided by Streamlit in your browser.

## Application Workflow
1. **Input Review**: Users can enter a movie review in the text box.
2. **Prediction**: The application uses the trained RNN model to classify the review as positive or negative.
3. **Display Results**: The sentiment and confidence score are displayed on the UI.

## Model Details
- **Architecture**: Simple RNN with layers designed for text processing and classification.
- **Word Embeddings**: Pre-trained embeddings (like GloVe or Word2Vec) or custom embeddings for text representation.
- **Dataset**: IMDb movie reviews dataset, preprocessed for training and testing.


## Dependencies
- **Streamlit**: For building the web application.
- **TensorFlow/Keras**: For building and deploying the Simple RNN model.
- **Pandas**: For data preprocessing.
- **Numpy**: For numerical computations.


## Future Enhancements
- Add more sophisticated architectures like LSTM/GRU for better sentiment classification.
- Include more advanced word embeddings such as BERT or FastText.
- Deploy the application on a cloud platform (e.g., Heroku, AWS).

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

