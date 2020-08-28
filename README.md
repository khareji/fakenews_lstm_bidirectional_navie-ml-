# fakenews_lstm_bidirectional_navie-ml
# Aim
Whether the news is fake or not .
# Introduction
Now days in era of social media every body is generating lots of news day by day but there is no proof that news is valid or not,
so here i have performed task in which there are three diffrent model which is predict whether the news is valid or not, using deep learning RNN(recurrent neural network).
# Data 
downloaded from kaggle
# LSTM
Long Short-Term Memory (LSTM) networks are a type of recurrent neural network capable of learning order dependence in sequence prediction problems.
This is a behavior required in complex problem domains like machine translation, speech recognition, and more.
LSTMs are a complex area of deep learning. It can be hard to get your hands around what LSTMs are, and how terms like bidirectional and sequence-to-sequence relate to the field
# BIDIRECTIONAL
Bidirectional LSTMs are an extension of traditional LSTMs that can improve model performance on sequence classification problems.
In problems where all timesteps of the input sequence are available, Bidirectional LSTMs train two instead of one LSTMs on the input sequence. The first on the input sequence as-is and the second on a reversed copy of the input sequence.
This can provide additional context to the network and result in faster and even fuller learning on the problem
# NAVIE BAYES
It is a classification technique based on Bayes’ Theorem with an assumption of independence among predictors. In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.
For example, a fruit may be considered to be an apple if it is red, round, and about 3 inches in diameter. Even if these features depend on each other or upon the existence of the other features,
all of these properties independently contribute to the probability that this fruit is an apple and that is why it is known as ‘Naive’.
Naive Bayes model is easy to build and particularly useful for very large data sets. Along with simplicity, Naive Bayes is known to outperform even highly sophisticated classification methods
# conclusion
further information realted to model is present inside a .pynb filr which include all three models(lstm,bidirectional,navie bayes)
