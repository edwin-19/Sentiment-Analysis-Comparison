# Comparison of machine learning models vs deep learning models
This repo was made to compare various models towards the task text classification for the twitter sentiment analysis dataset,
Might try out more dl based models such as distilbert but not sure if i have the time

Models used are:
- XGBoost
- LightGBM
- Bert Base Uncased
- T5-Small (Seemed to have better results for 1 epoch)

| Model             | Accuracy |
|-------------------|----------|
| XGBoost           | 0.74     |
| LightBGM          | 0.61     |
| BERT Base Uncased | 0.88     |
| T5-Small(1-Epoch) | 0.85     |