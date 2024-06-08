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
    <li><a href="#Metode-yang-Digunakan">Metode yang Digunakan</a>
    </li>
    <li><a href="#Referensi">referensi</a></li>
    <li><a href="#Literatur">referensi</a></li>
    <li><a href="#License">Lisensi</a></li>
    <li><a href="#Benchmark-Model-Accuracy-Results">Benchmark Model Accuracy Results</a></li>
    <li><a href="#Report">Report</a></li>
    <li><a href="#Teams">Teams</a></li>
  </ul>
</details>


## **Dataset**



## **Metode yang Digunakan**
![Picture1](https://github.com/rizky-22017-mhs-unesa-ac-id/Sentiment-Analysis-of-KIPK-Recipients-based-on-Tweets-from-X/assets/82692777/6fc06fc3-8c73-4a5f-b4d0-05d059b0f6c3)



## **Referensi**
 * https://github.com/louisowen6/NLP_bahasa_resources
 * https://github.com/onpilot/sentimen-bahasa?tab=readme-ov-file
 * https://github.com/ShinyQ/Final-IFest-2021_Analisis-Sentimen-Kebijakan-PPKM-Pemerintah-IndoBERT-IndoBERTweet/tree/main

## **Literatur**
 * https://link.springer.com/content/pdf/10.1007/s00521-022-08186-1.pdf


## **License**
MIT


## **Benchmark Model Accuracy Results**

| Model        |         Generic        |          GloVe         |          FastText      |
| -----------  | ---------------------- | ---------------------- | ---------------------- |
| LSTM         |     0.768              |        0.761           |        0.782           |
| GRU          |     0.761              |        0.766           |        0.78            |
| biLSTM       |     0.75               |     **0.795**⭐        |        0.778           |

dapat dilihat dari tabel diatas bahwa kombinasi biLSTM dengan glove memberikan akurasi tertinggi.😊


## **Report**

<div style="text-align: center;">
  <a href="https://lookerstudio.google.com/reporting/1cd78423-a8d7-496f-bea2-35fce8ee06f7/page/ynr1D" target="_blank">
    <img src="https://github.com/rizky-22017-mhs-unesa-ac-id/Sentiment-Analysis-of-KIPK-Recipients-based-on-Tweets-from-X/assets/82692777/3d996ddc-142a-4138-8888-0d2711dca0ae" alt="Untitled video" />
  </a>
</div>


## **Teams**

<div align="center">
  <table style="margin: auto;">
    <tr>
      <td align="center">
  <a href="https://github.com/rizkyyanuark">
    <img src="https://avatars.githubusercontent.com/u/82692777?v=4" width="100px;" alt="RizkyYanuarK"/>
  </a>
  <br />
  <sub>RizkyYanuarK</sub>
</td>
<td align="center">
  <a href="https://github.com/Dianayuww">
    <img src="https://avatars.githubusercontent.com/u/167867871?v=4" width="100px;" alt="Dian Ayu Fauziah"/>
  </a>
  <br />
  <sub>Dian Ayu Fauziah</sub>
</td>
  </table>
</div>
