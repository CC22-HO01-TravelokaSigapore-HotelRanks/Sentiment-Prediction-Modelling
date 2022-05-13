# Hotel Reviews Sentiment Prediction

Notebooks of our research and modelling for Sentiment Prediction of Hotel Reviews. This pre-trained model can be downloaded through this [link](https://drive.google.com/drive/u/2/folders/1A7N_McAxnxrThlDyArJXr0_k-nHPDfiI). This model was trained on Hotel Reviews data on [Kaggle](https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe). This model is also utilized on Pre-Trained Embedding on Multilingual Embeddings by Google that can be found [here](https://tfhub.dev/google/universal-sentence-encoder-multilingual/3).

| Information     | Value                                                                           |
|-----------------|---------------------------------------------------------------------------------|
| Model Structure | Pre Trained Embedding - Dense - Dense(Sigmoid)                                  |
| Model Input     | List of strings, uncased (lower string), alphabetic (word only)                 |
| Model Output    | Sigmoid values [0..1] where 0 is negative sentiment and 1 is positive sentiment |

This model is being implemented on out system.

CC22-HO01 ML Teams.