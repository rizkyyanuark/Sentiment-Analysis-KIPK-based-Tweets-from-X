<div align="center">
  <h1>Sentiment Analysis of KIPK Recipients based on Tweets from X</h1>
  <blockquote>
    Project ini memanfaatkan metode LSTM dalam memahami konteks temporal dan word embedding untuk merepresentasikan makna kata. Dengan kombinasi ini, model dapat memahami makna dan sentimen di balik setiap tweet. 
    <br>
    Tujuan utama project ini adalah untuk menganalisis sentimen penerima KIPK melalui tweet. Hasilnya akan memberikan pemahaman tentang persepsi masyarakat terhadap program ini dan memberikan wawasan tentang bagaimana meningkatkan program ini di masa mendatang.
  </blockquote>
</div>

<details>
  <summary>🏁 Table of Contents</summary>
  <ul>
    <li><a href="#Dataset">Dataset</a></li>
    <li><a href="#Teknologi-yang-Digunakan">Teknologi yang Digunakan</a>
    </li>
    <li><a href="#Infografik">Kontribusi</a></li>
    <li><a href="#Referensi">referensi</a></li>
    <li><a href="#Literatur">referensi</a></li>
    <li><a href="#License">Lisensi</a></li>
    <li><a href="#File">File</a></li>
    <li><a href="#Teams">Teams</a></li>
  </ul>
</details>

## **Benchmark Model Accuracy Results**

| Model        |         Generic        |          GloVe         |          FastText      |
| -----------  | ---------------------- | ---------------------- | ---------------------- |
| LSTM         |     0.768              |        0.761           |        0.782           |
| GRU          |     0.761              |        0.766           |        0.78            |
| biLSTM       |     0.75               |     **0.795**⭐        |        0.778           |

dapat dilihat dari tabel diatas bahwa kombinasi biLSTM dengan glove memberikan akurasi tertinggi.😊
