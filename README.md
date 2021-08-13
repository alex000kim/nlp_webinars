# NLP webinars

### Webinar materials

- [Hotel Review Prediction](https://github.com/alex000kim/nlp_webinars/blob/main/1_HotelReviewPrediction.ipynb)
  
  Learning objectives
  
  - Learn how to prepare text data for predictive modelling. We'll compare two techniques: TF-IDF and word2vec
  
  - Train and compare the performance of two predictive models: linear regression (from `sklearn` library) and gradient boosting tree regression (from `xgboost` library)

- [Movie Plot Similarity Search](https://github.com/alex000kim/nlp_webinars/blob/main/2_MoviePlotSimilaritySearch.ipynb)
  
  Learning objectives
  
  - Learn how vectorize text using language transformer models
  - Learn how to perform information retrieval (aka similarity search) on text data

### Prerequisites

- [pipenv](https://pipenv.pypa.io/en/latest/)

- [jupyter](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)

### Setup

```bash
# Create virtual environment
pipenv shell
# Install dependencies
pipenv install
# Register this environment's python kernel in jupyter
python -m ipykernel install --user --name nlp-webinars --display-name "Python (nlp-webinars)"
```

After launching jupyter server, verify that the right kernel is used.