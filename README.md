This project solve a problem about Multi-label Text Classification through Multilabel Sentiment Analysis. In particular, the task is to predict the labels contained in a Tweet. \n
Dataset is the Multilabel Sentiment Analaysis dataset (SemEval-2018 Task 1)
This project will experiment 5 models, including:
1. TF-IDF + Naive Bayes: Utilizing the TF-IDF vectorization technique coupled with the Naive Bayes classifier provides a solid baseline. Naive Bayes is known for its efficiency and simplicity, making it well-suited for text classification tasks.
2. TF-IDF + SVM: SVMs excel in handling high-dimensional data and are particularly effective in scenarios where clear decision boundaries are crucial.
3. BiLSTM: BiLSTM is capable of understanding the sequential nature of textual data.
4. BERT + CNN: Integrating BERT embeddings with CNN introduces a powerful combination of pre-trained contextual embeddings and the ability to capture hierarchical features. This model is expected to excel in extracting intricate patterns.
5. BERT + LSTM: Merging BERT embeddings with LSTM enhances the model’s capacity to retain information over longer sequences.
After all compare the result to see which models exhibit superior performance in capturing the nuanced emotional expressions present in the dataset.
