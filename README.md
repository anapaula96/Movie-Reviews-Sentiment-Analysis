# IMDb Movie Reviews Sentiment Analysis

## Project Overview

This project aims to classify IMDb movie reviews as positive or negative using Natural Language Processing (NLP) techniques and machine learning models. The dataset used contains 50,000 labeled movie reviews, split evenly into training and testing sets.

## Dataset

The dataset contains:
- 25,000 positive reviews
- 25,000 negative reviews

The reviews are stored in text files in two main directories:
- `train/`: Contains training data with subdirectories `pos/` and `neg/` for positive and negative reviews respectively.
- `test/`: Contains testing data with subdirectories `pos/` and `neg/` for positive and negative reviews respectively.

## Project Structure

The project files are organized as follows:
- `notebooks/`: Jupyter notebooks containing the code for data preprocessing, model training, and evaluation.
- `data/`: Directory containing the IMDb dataset.
- `models/`: Directory to save the trained models and vectorizers.
- `README.md`: Project documentation.

## Installation

To get started, clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
pip install -r requirements.txt
