# Hate Comments Detection using Deep Learning

This project is a multi-class text classification system that detects and categorizes tweets/comments as:
- Hate Speech 
- Offensive Language 
- Neutral

Built using Python, TensorFlow/Keras, and NLP preprocessing techniques, the model leverages a Bidirectional LSTM architecture to achieve high accuracy on social media text data.


## Tech Stack

- Python  
- TensorFlow / Keras  
- Bidirectional LSTM  
- NLTK  
- Pandas  
- Jupyter Notebook  


## Dataset

The dataset contains labeled tweets/comments, categorized as:
- `0`: Hate speech  
- `1`: Offensive language  
- `2`: Neutral

You can find the dataset file in this repo as `Dataset.csv`.


##  Preprocessing

- Lowercasing  
- Punctuation removal  
- Tokenization  
- Stopword removal  
- Lemmatization


##  Model Architecture

- Embedding Layer  
- Bidirectional LSTM (16 units)  
- Dense Layer (512 units, ReLU, L1 regularization)  
- Batch Normalization  
- Dropout (0.3)  
- Output Layer (Softmax)


## Training Details

- Optimizer: Adam  
- Loss Function: Categorical Crossentropy  
- Callbacks: EarlyStopping, ReduceLROnPlateau  
- Achieved ~91% validation accuracy



