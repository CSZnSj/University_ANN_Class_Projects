The focus of this project is to develop a machine learning model to detect hate speech in social 
media texts. The task is to classify text data into three categories: 0 (not hated), 1 (racism) and 2 
(xeno). To achieve this, we leveraged an LSTM-based neural network, which is well suited to 
processing sequential data such as text. The data comes from various Kaggle datasets, including 
the Hate Speech Detection Curated Dataset, Racism Data and Xeno Data. These datasets were 
pre-processed, tokenized, and used to build a comprehensive vocabulary. Our model architecture 
included an embedding layer, a bidirectional LSTM layer, and fully connected layers with ReLU 
activation. The model was trained using the Adam optimizer and evaluated for accuracy, precision, 
recall and F1 score
