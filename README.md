# Using LSTM for Sentiment Analysis of Amazon Reviews

LSTM built using PyTorch to predict whether a certain review is positive or negative (sentiment).

## 🍟 Results

A noticeable plateau occurs at around Step 5000 at the first epoch. A decrease in alpha (learning rate) is recommended and an increase in the number of embedding dimensions and hidden dimensions. 

```
Test Loss: 0.211
Test Accuracy: 91.692%
```



## 🍰 Training the Model
- Download the [dataset](https://www.kaggle.com/bittlingmayer/amazonreviews?)
- Extract the dataset
- Run the jupyter notebook

## ⚙️ Requirements

- Python >= 3.7.0
- Jupyter Notebook
- NumPy
- PyTorch
- CUDA 11.0
- Optional: tqdm


## 📜 Dataset
[Amazon Reviews for Sentiment Analysis (Kaggle)](https://www.kaggle.com/bittlingmayer/amazonreviews?)