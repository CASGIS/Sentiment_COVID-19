01_sentiment/ : sentiment imputation, see the repository: https://github.com/MIT-SUL-Team/global-sentiment

    - data: the traning and labeled_data for the global sentiment imputation
    - dict/sentiment_dicts: the emoji, hedonometer, and LIWC dictionaries
    - models: the multilingual data for the sentiment
    - notebooks: `sentiment clf evaluator.ipynb`
    - output
    - report
    - src: main model and sentiment imputation folders
      - `main_geography_imputer.py`
      - `main_sentiment_aggregator.py`
      - `main_sentiment_imputer.py`
      - `setup_emb_clf.py`
      - `setup_liwc.py`
      - utils: functions used for the sentiment imputation
        - `aggregation_utils.py`
        - `data_read_in.py`
        - `dict_sentiment_imputer.py`
        - `emb_clf_setup_utils.py`
        - `emb_sentiment_imputer.py`