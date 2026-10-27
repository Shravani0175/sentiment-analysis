# Sentiment Analysis Using NLP

## About the Project

I built this project to explore how machine learning can understand the sentiment behind text. The model takes a movie review as input and predicts whether the review expresses a positive or negative sentiment.

For this project, I used the IMDB movie review dataset and built a simple neural network using TensorFlow and Keras. It was a good way to get hands-on experience with text preprocessing, word representations, and training a model for text classification.

## Technologies Used

- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Natural Language Processing (NLP)
- Jupyter Notebook

## Dataset

I used the IMDB movie review dataset, which contains 50,000 movie reviews labelled as positive or negative.

- 25,000 reviews for training
- 25,000 reviews for testing
- Two sentiment classes: positive and negative

The dataset is loaded directly through TensorFlow's Keras dataset utilities.

## How It Works

First, I loaded the movie review dataset and prepared the text data so it could be used by the model. Since the reviews have different lengths, I padded or truncated them to a fixed length.

I then built a neural network with an embedding layer to represent words numerically, followed by a global average pooling layer and dense layers to predict sentiment.

After training the model, I evaluated it on the test dataset and plotted the training and validation accuracy and loss. I also tested the model with a few sample sentences to see how it classified positive and negative reviews.

## Model Results

Test Accuracy: Add your actual test accuracy here.

Test Loss: Add your actual test loss here.

## How to Run

Clone the repository:

```bash
git clone https://github.com/Shravani0175/sentiment-analysis.git
cd sentiment-analysis
```

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib
```

Open the notebook:

```bash
jupyter notebook sentiment-analysis.ipynb
```

Run the notebook cells in order. An internet connection is required the first time the dataset is downloaded.

## What I Learned

Through this project, I got practical experience with text classification, word embeddings, neural networks, and model evaluation. I also learned how to visualize training results and test predictions on sample text.

## Future Improvements

- Improve text preprocessing and handle punctuation more effectively.
- Experiment with different neural network architectures.
- Test the model on more varied text.
- Build a simple web interface where users can enter a review and see the predicted sentiment.

## Author

Shravani Dandane
