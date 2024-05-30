# Sentiment Analysis of KIPK Recipients based on Tweets from X
## **Benchmark Model Accuracy Results**

| Model        |         Generic        |          GloVe         |          FastText      |
| -----------  | ---------------------- | ---------------------- | ---------------------- |
| LSTM         |     0.768              |        0.761           |        0.782           |
| GRU          |     0.761              |        0.766           |        0.78            |
| biLSTM       |     0.75               |     **0.795**⭐        |        0.778           |

As seen above the biLSTM + GloVe models give the highest accuracy.
