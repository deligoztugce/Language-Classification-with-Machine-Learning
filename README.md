# Language-Classification-with-Machine-Learning

## Project Overview

This project performs language detection on textual data using machine learning techniques. The model identifies the language of a given text input, trained on a multi-class dataset consisting of 22 languages. The dataset includes 1000 sentences per language, offering a well-balanced dataset for training and testing.

### Key Features:
- Multilingual text data (22 languages)
- Utilizes CountVectorizer to convert text into a bag of words
- Trained using the Multinomial Naive Bayes algorithm
- 95.32% accuracy in language prediction

## Dataset

The dataset used for this language detection task is a CSV file that contains two columns:
1. **Text**: The sentence in a particular language.
2. **Language**: The language of the corresponding sentence.

### Languages in the Dataset:
- Estonian
- Swedish
- Thai
- Tamil
- Dutch
- Japanese
- Turkish
- Latin
- Urdu
- Indonesian
- Portuguese
- French
- Chinese
- Korean
- Hindi
- Spanish
- Pashto
- Persian
- Romanian
- Russian
- English
- Arabic

The dataset consists of 1000 sentences per language and includes 22 different languages.

## Requirements

To run this project, you need to install the following Python libraries:

- pandas
- numpy
- scikit-learn

You can install them using pip:

```bash
pip install pandas numpy scikit-learn
