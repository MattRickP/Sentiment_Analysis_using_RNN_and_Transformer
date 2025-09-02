# Sentiment_Analysis_using_RNN_and_Transformer
  
In this project, we examine the 'emotions' dataset, which comprises 416.809 text segments extracted from Twitter (now called "X") messages. Each segment is paired with a label that identifies the predominant emotion conveyed.  
The dataset categorizes emotions into six classes: 
- sadness (0)
- joy (1)
- love (2) 
- anger (3)
- fear (4)
- surprise (5)  
  
We will explore both a RNN and an encoder-only Transformer by training models from both architectures on the same linguistic tasks:  
We prepare the Twitter texts for **sentiment analysis** using Byte Pair Encoding (BPE). The RNN will feature bidirectional layers. The architecture of the encoder-only transformer model will mostly follow the standard configuration. We will use Optuna for hyperparameter optimization.  
  
The two models will be trained in separate notebooks.
  
The dataset used in this repository is the "emotions" dataset, originally created by Nidula Elgiriyewithana. The dataset is hosted on Kaggle.  
https://www.kaggle.com/datasets/nelgiriyewithana/emotions/data  
https://doi.org/10.34740/kaggle/dsv/7563141  
