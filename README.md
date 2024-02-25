# Fake News Classifier using NLP

## Overview

This project implements a Fake News Classifier using Natural Language Processing (NLP) techniques. The goal is to distinguish between fake and real news articles based on their content.

## Dataset

The project uses the [Fake News Dataset](https://www.kaggle.com/c/fake-news/data#) from Kaggle. The dataset consists of labeled news articles as either "fake" or "real."

## Project Structure

- **FakeNewsCount_vectorizer.ipynb**: Jupyter Notebook containing the code for the project.
- **README.md**: This file, providing an overview of the project.

## Dependencies

Make sure you have the following Python packages installed:

```bash
pip install pandas scikit-learn nltk matplotlib
```
## Usage
Clone the repository:
```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```
Open and run the Jupyter Notebook FakeNewsCount_vectorizer.ipynb:

```bash
jupyter notebook FakeNewsCount_vectorizer.ipynb
```
Follow the instructions in the notebook to execute and understand the code.

## Key Steps
1. Data Preprocessing:

Loading the dataset and handling missing values.
Text cleaning, including removing non-alphabetic characters, converting to lowercase, and stemming.

2. Feature Extraction:

Using CountVectorizer to convert text data into a Bag of Words model.

3. Model Training:

Using the Multinomial Naive Bayes algorithm and the Passive Aggressive Classifier for classification.

4. Model Evaluation:

Calculating accuracy and creating a confusion matrix.

5. Hyperparameter Tuning:

Adjusting the hyperparameter (alpha) for the Multinomial Naive Bayes classifier.


## Results

- Multinomial Naive Bayes Accuracy: 90.2%
  ![Multinomial Naive Bayes Confusion Matrix](https://example.com/path/to/multinomial_nb_confusion_matrix.png)

- Passive Aggressive Classifier Accuracy: 91.9%
  ![Passive Aggressive Classifier Confusion Matrix](https://github.com/monalisaburma/Fake-News-Classifier-using-NLP/assets/122416015/aa184df4-f7ca-4fa0-8b1b-2158e868f903)



## Future Improvements
- Experiment with different NLP techniques and models.
- Fine-tune hyperparameters for better performance.
- Explore advanced deep learning models for text classification.


Feel free to reach out for any questions or suggestions!
