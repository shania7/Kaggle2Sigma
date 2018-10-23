# Kaggle2Sigma
Trello: https://trello.com/kaggle2sigma
Google Drive: https://drive.google.com/drive/folders/1pW6ZFw9es4CLpMq67rbtjhxD20LBLmGH?usp=sharing

## Project Plan
1. Brain-storming ideas and research for relevant techniques and resources
2. Baseline models
3. Implementation of ideas and experiments
4. Consolidation
5. (1)-(4) iterations

## 1. Ideas & Research

- To find out stocks similarity and represent it in the model
    - stocks embedding?

- News Summarisation:
    - word/document embeddings: word2vec, fasttext, NNLM - google news, universal sentence encoder
    - attention mechanism: certain stocks paying attention to certain news

- Quantify stock price:
    - Time series features engineering: 
        i. Reference to EEG detection challenge:http://blog.kaggle.com/2015/10/05/grasp-and-lift-eeg-detection-winners-interview-3rd-place-team-hedj/
    - Percentage changes
    - Price trend: smoothed gradient, moving average etc.
    - Volatility: price variations