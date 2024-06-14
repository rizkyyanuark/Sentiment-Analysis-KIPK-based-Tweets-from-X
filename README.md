<div align="center">
  <h1>Sentiment Analysis of KIPK Recipients based on Tweets from X</h1>
  <blockquote>
    <p>Project ini memanfaatkan metode LSTM dalam memahami konteks temporal dan word embedding untuk merepresentasikan makna kata. Dengan kombinasi ini, model dapat memahami makna dan sentimen di balik setiap tweet.</p>
    <p>Tujuan utama project ini adalah untuk menganalisis sentimen penerima KIPK melalui tweet. Hasilnya akan digunakan untuk memberikan wawasan tentang bagaimana program ini diterima oleh masyarakat.</p>
  </blockquote>
</div>

<details>
  <summary>🏁 Table of Contents</summary>
  <ul>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#metode-yang-digunakan">Metode yang Digunakan</a></li>
    <li><a href="#referensi">Referensi</a></li>
    <li><a href="#literatur">Literatur</a></li>
    <li><a href="#license">Lisensi</a></li>
    <li><a href="#benchmark-model-accuracy-results">Benchmark Model Accuracy Results</a></li>
    <li><a href="#report">Report</a></li>
    <li><a href="#Hasil Analisis">Hasil Analisis</a></li>
    <li><a href="#teams">Teams</a></li>
  </ul>
</details>

## Dataset

Pada proyek ini, kami membagi dataset menjadi dua bagian: dataset train dan dataset test.

### Dataset Train
Dataset train digunakan untuk melatih model dan terdiri dari dua sumber data utama:

1. **Twitter Emotion Dataset**:
    - **Deskripsi**: Dataset ini berisi tweet-tweet berlabel emosi seperti anger, sadness, dan happy, yang dikelompokkan sesuai dengan sentimen positif, negatif, dan netral.
    - **Jumlah Data**: ±4000 tweet
    - **Sumber**: [Twitter Emotion Dataset](https://github.com/meisaputri21/Indonesian-Twitter-Emotion-Dataset/blob/master/Twitter_Emotion_Dataset.csv)

2. **PPKM Dataset**:
    - **Deskripsi**: Dataset ini terdiri dari tweet-tweet yang berisi opini masyarakat tentang kebijakan PPKM.
    - **Jumlah Data**: ±71000 tweet
    - **Sumber**: [PPKM Dataset](https://www.kaggle.com/datasets/anggapurnama/twitter-dataset-ppkm)

### Dataset Scraping
Dataset Scraping digunakan untuk mengetahui sentimen dengan model yang telah dilatih. Dataset ini diperoleh melalui proses scraping dari X:

1. **Scraped Twitter Data**:
    - **Deskripsi**: Dataset ini berisi tweet-tweet terbaru yang dikumpulkan dengan menggunakan teknik web scraping dari X. Tweet-tweet ini berhubungan dengan penerima KIPK dan opini mereka.
    - **Jumlah Data**: ±4.000 tweet
    - **Tanggal Pengumpulan**: Mei 2024
    - **Scraper**: [Blog](https://helmisatria.com/blog/updated-crawl-data-twitter-x-maret-2024)

### Tujuan Penggunaan Dataset
- **Dataset Train**: Melatih model untuk mengenali dan mengklasifikasikan sentimen dari tweet.
- **Dataset Scrape**: Dataset hasil scraping ini akan digunakan untuk menganalisis sentimen publik dengan model yang telah dilatih menggunakan dataset pelatihan.


## Metode yang Digunakan
![Metode yang Digunakan](https://github.com/rizky-22017-mhs-unesa-ac-id/Sentiment-Analysis-of-KIPK-Recipients-based-on-Tweets-from-X/assets/82692777/6fc06fc3-8c73-4a5f-b4d0-05d059b0f6c3)

## Referensi
* [NLP Bahasa Resources](https://github.com/louisowen6/NLP_bahasa_resources)
* [Sentimen Bahasa](https://github.com/onpilot/sentimen-bahasa?tab=readme-ov-file)
* [Analisis Sentimen Kebijakan PPKM](https://github.com/ShinyQ/Final-IFest-2021_Analisis-Sentimen-Kebijakan-PPKM-Pemerintah-IndoBERT-IndoBERTweet/tree/main)

## Literatur
* [Springer Link](https://link.springer.com/content/pdf/10.1007/s00521-022-08186-1.pdf)

## License
MIT

## Benchmark Model Accuracy Results

| Model  |   Generic   |    GloVe     |   FastText  |
|--------|-------------|--------------|-------------|
| LSTM   |    0.768    |    0.761     |    0.782    |
| GRU    |    0.761    |    0.766     |    0.780    |
| biLSTM |    0.750    |  **0.795**⭐  |    0.778    |

Dapat dilihat dari tabel di atas bahwa kombinasi biLSTM dengan GloVe memberikan akurasi tertinggi. 😊

## Report

<div align="center">
  <a href="https://lookerstudio.google.com/reporting/1cd78423-a8d7-496f-bea2-35fce8ee06f7/page/ynr1D" target="_blank">
    <img src="https://github.com/rizky-22017-mhs-unesa-ac-id/Sentiment-Analysis-of-KIPK-Recipients-based-on-Tweets-from-X/assets/82692777/3d996ddc-142a-4138-8888-0d2711dca0ae" alt="Report Video" width="600"/>
  </a>
</div>

## Hasil Analisis
<div align="center">
  <p>
    Berdasarkan hasil analisis sentimen, <strong>Universitas Diponegoro</strong> menjadi pusat perhatian di Twitter. Dalam rentang waktu 10 Juli 2023 hingga 30 April 2024, Universitas Diponegoro paling banyak mendapatkan mention dengan kata kunci <strong>‘KIPK’</strong>. Hal ini menunjukkan bahwa ada banyak diskusi dan minat yang signifikan terkait dengan Universitas Diponegoro dan program KIPK selama periode tersebut.
  </p>
</div>

## Teams
<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/rizkyyanuark">
          <img src="https://avatars.githubusercontent.com/u/82692777?v=4" width="100px;" alt="Rizky Yanuar K"/>
        </a>
        <br />
        <sub><b>Rizky Yanuar K</b></sub>
      </td>
      <td align="center">
        <a href="https://github.com/Dianayuww">
          <img src="https://avatars.githubusercontent.com/u/167867871?v=4" width="100px;" alt="Dian Ayu Fauziah"/>
        </a>
        <br />
        <sub><b>Dian Ayu Fauziah</b></sub>
      </td>
    </tr>
  </table>
</div>
