# Fake News Classification

This project aims to classify news articles as either **Fake** or **Real** using machine learning techniques.  
We compare the performance of two models: **Logistic Regression** and **Naive Bayes**, both trained and evaluated on the same dataset.

## Dataset

- `Fake.csv`: Contains fake news articles.
- `True.csv`: Contains real news articles.

## Getting Started

1. Clone the repository.
2. Install required dependencies (see below).
3. Run the Jupyter notebook `fake_news.ipynb` to train and evaluate both models.

## Requirements

- Python 3.x
- pandas
- scikit-learn
- numpy
- jupyter

Install dependencies with:
```sh
pip install pandas scikit-learn numpy jupyter
```

## Usage

Open the notebook:
```sh
jupyter notebook fake_news.ipynb
```
Follow the steps in the notebook to preprocess data, train both models, and compare their performance using accuracy, confusion matrix, and visualizations.

## Project Structure

- `fake_news.ipynb`: Main notebook for data analysis, model training, and comparison.
- `Fake.csv`: Dataset of fake news articles.
- `True.csv`: Dataset of real news articles.
- `README.md`: Project documentation.

## License

This project is for educational