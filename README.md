# TFIDF or embedding

in this research i use bbc news dataset with 5 category 

there are 11 scenarios in this research: 
- Embedding Only
- TFIDF + Dense
- TFIDF + LSTM but only 1 step
- TFIDF + LSTM with many step
- Embedding concat tfidf then feed to LSTM
- LSTM then concat with TFIDF
- SVD + Dense
- SVD + LSTM but only 1 step
- SVD + LSTM with many step
- Embedding concat svd then feed to LSTM
- LSTM then concat with SVD

here is the conclusion of accuracy and val accuracy among them :
| arch  | acc | val acc |
| ------------- | ------------- | ------------- |
| Embedding Only | 99.27% | 90.79% |
| TFIDF + Dense | 99.27% | 91.01% |
| TFIDF + LSTM but only 1 step | 99.49% | 91.24% |
| TFIDF + LSTM with many step | 63.37% | 62.7% |
| Embedding concat tfidf then feed to LSTM | 100% | 92.81% |
| LSTM then concat with TFIDF | 99.89% | 93.93% |
| SVD + Dense | 98.99% | 5.39% |
| SVD + LSTM but only 1 step | 99.78% | 6.29% |
| SVD + LSTM with many step | 23.71% | 22.25% |
| Embedding concat svd then feed to LSTM | 100% | 90.79% |
| LSTM then concat with SVD | 100% | 93.26% |

<b>Here is the architecture of Embedding Only</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/Embedding%20Only.png></p>  
<br><br>
<b>Here is the architecture of TFIDF + LSTM but only 1 step</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/TFIDF%20+%20LSTM%20but%20only%201%20step.jpg></p>  
<br><br>
<b>Here is the architecture of Embedding concat svd then feed to LSTM</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/Embedding%20concat%20svd%20then%20feed%20to%20LSTM.jpg></p>  
<br><br>
<b>Here is the architecture of SVD + Dense</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/SVD%20+%20Dense.jpg></p>  
<br><br>
<b>Here is the architecture of TFIDF + LSTM with many step</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/TFIDF%20+%20LSTM%20with%20many%20step.jpg></p>  
<br><br>
<b>Here is the architecture of LSTM then concat with SVD</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/LSTM%20then%20concat%20with%20SVD.jpg></p>  
<br><br>
<b>Here is the architecture of TFIDF+Dense</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/TFIDF+Dense.jpg></p>  
<br><br>
<b>Here is the architecture of SVD + LSTM with many step</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/SVD%20+%20LSTM%20with%20many%20step.jpg></p>  
<br><br>
<b>Here is the architecture of Embedding concat tfidf then feed to LSTM</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/Embedding%20concat%20tfidf%20then%20feed%20to%20LSTM.jpg></p>  
<br><br>
<b>Here is the architecture of SVD + LSTM but only 1 step</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/SVD%20+%20LSTM%20but%20only%201%20step.jpg></p>  
<br><br>
<b>Here is the architecture of LSTM then concat with TFIDF</b>
<br>
<p align="center"><img width="500" height="500" src=https://raw.githubusercontent.com/okyx/TFIDF-or-embedding-/main/foto/LSTM%20then%20concat%20with%20TFIDF.jpg></p>  
<br><br>
