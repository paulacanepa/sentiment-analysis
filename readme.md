# Sentiment Analysis

## Description

In this project I will conduct 3 different approaches to implement a sentiment analysis. The target is a categorical variable that can assume the value of: positive, negative or neutral. 

The dataset was get from Kaggle -
https://www.kaggle.com/datasets/sbhatti/financial-sentiment-analysis


## Installation

Requirements: Python and Conda

Create a conda environment with the libraries in the .yml file.

```bash
conda env create -f environment.yml
```

## Usage
To see the experiments, you should run the notebooks using the kernel created with conda "sentiment-analysis-env"


- PC_01_exp_countvectorizer
         
         This notebooks contains the training, evaluation and predictions of a classification for sentiment analysis using CountVectorizer and tf-idf. 

- PC_02_exp_keras
        
        This notebooks contains the training, evaluation and predictions of a classification for sentiment analysis using keras and embedings. 

- PC_03_exp_BERT
        
        This notebooks contains the training, evaluation and predictions of a classification for sentiment analysis using the pre-trained BERT model. 

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

## References

Some links that I use as a reference:

- https://github.com/jessica-arroyo/kaggle_movie_reviewsv
- https://www.kaggle.com/code/bertcarremans/using-word-embeddings-for-sentiment-analysis
- https://huggingface.co/docs/transformers/model_doc/bert 
