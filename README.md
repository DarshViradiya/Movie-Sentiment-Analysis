# Movie-Sentiment-Analysis

This project implements a deep learning model to classify movie reviews into 5 sentiment categories using the Kaggle Sentiment Analysis on Movie Reviews dataset. The model is built using Keras with stacked GRU and Bidirectional GRU layers, trained on tokenized and padded sequences of movie review phrases. It achieves ~67% validation accuracy and includes preprocessing, training, evaluation (confusion matrix, F1 score), and prediction on custom input.

# Key Features:

<span style="color:#f39c12"><b>1.</b></span> Custom text cleaning pipeline (punctuation removal, lowercase, padding)  
<span style="color:#3498db"><b>2.</b></span> Tokenization with Keras and dynamic padding  
<span style="color:#2ecc71"><b>3.</b></span> Deep sequential model with:  
  • Embedding layer  
  • GRU + Bi-GRU + Dropout layers  
  • Dense softmax output for 5-class sentiment prediction  
<span style="color:#9b59b6"><b>4.</b></span> Metrics: Validation Accuracy, Weighted F1 Score, and Confusion Matrix  
<span style="color:#e74c3c"><b>5.</b></span> Supports prediction on new user-inputted reviews

# Technologies Used:

<span style="color:#1abc9c">•</span> Python, Pandas, NumPy  
<span style="color:#1abc9c">•</span> TensorFlow / Keras  
<span style="color:#1abc9c">•</span> scikit-learn  
<span style="color:#1abc9c">•</span> Matplotlib & Seaborn  
<span style="color:#1abc9c">•</span> Google Colab + Kaggle API

# Sample Prediction:

Input Text 1:"Absolutely fantastic! One of the best films I've seen this year."  
Predicted Sentiment Class: 4 (Very Positive)  

Input Text 2:"Good movie and plot was good but character developing could be better"  
Predicted Sentiment Class: 2 (Moderate)
