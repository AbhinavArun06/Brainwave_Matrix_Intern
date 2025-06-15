# Fake News Detection System

![Project Banner](https://via.placeholder.com/800x200?text=Fake+News+Detection+with+ML)

A machine learning model to classify news articles as real or fake using BERT and XGBoost.

## Features
- **Two implementations**: BERT (Transformer) and XGBoost (Boosting)
- **Preprocessing pipeline**: Text cleaning, TF-IDF vectorization
- **Model evaluation**: Accuracy, Precision, Recall metrics
- **Prediction API**: Ready-to-use prediction function

## Installation
```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
pip install -r requirements.txt
```

## Usage
```python
from predict import predict_news

result = predict_news("Your news text here")
print(result)  # Output: "Real News" or "Fake News"
```

## Results
| Model       | Accuracy | Precision | Recall |
|-------------|----------|-----------|--------|
| BERT        | 98.2%    | 98.1%     | 98.3%  |
| XGBoost     | 96.7%    | 96.5%     | 96.8%  |

## Dataset
Dataset from [Kaggle Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

## Contributors
- Abhinav Arun (abhinavarun3k@gmail.com)
