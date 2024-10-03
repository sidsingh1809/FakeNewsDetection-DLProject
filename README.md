# FakeNewsDetection-DLProject

## Abstract
The growth of technology has presented new challeng-es in distinguishing between legitimate and fake news. The rapid dissemination of news on various  platforms has rendered traditional techniques of news verification ineffective. In this project, we propose the use of BERT, LSTM, Bi-LSTM models for spotting fake news on 2 datasets, i.e., ISOT and LIAR. BERT, a powerful deep learning model for natural language processing, captures the contextual meaning of words and phrases, while LSTM models excel in modeling sequential data. BERT and LSTM models are then fine-tuned on this dataset to classify news as real or fake. The models extract meaningful features from the text, incorporating the contextualized word embed-dings from BERT and the sequential dependencies from LSTM. Overall, deep learning is a promising tool for fake news detection. However, it is important to be aware of the challenges and limitations of this approach.


## Result
For ISOT dataset - 

|Table|BERT|LSTM|Bi-LSTM|
| --- | --- | --- | --- |
|Train Accuracy	|0.8858	|0.9924	|0.9951|
|Test Accuracy |0.8991	|0.9650	|0.9669|
|Train Loss	|0.2735	|0.0258	|0.0152|
|Test Loss |0.2439 |0.1624 |0.1306|

For LIAR dataset - 

|Table|BERT|LSTM|Bi-LSTM|
| --- | --- | --- | --- |
|Train Accuracy	|0.6466	|0.6999	|0.6438|
|Test Accuracy |0.6372 |0.6614 |0.6590|
Train Loss |0.6440 |0.5785 |0.6472|
Test Loss	|0.6445	|0.6348	|0.6185|


### Kindly make the following changes to run the codes - 
In code block 4 of both files, kindly add the paths to data according to where you save it on your system/drive.

Kindly use the dataset on this link - https://drive.google.com/drive/folders/1NQ1r66wbZ9fuJtwplW-RlfJvz3L0SVyb <br>
ISOT - News-dataset folder<br>
LIAR - data folder<br>

### Packages required to run the code - 
1 numpy<br>
2 pandas<br>
3 seaborn<br>
4 matplotlib<br>
5 wordcloud<br>
6 nltk<br>
7 gensim<br>
8 sklearn<br>
9 tensorflow<br>
10 transformers<br>
11 torch<br>
12 tensorflow_hub<br>
13 tensorflow_text<br>
14 keras<br>
