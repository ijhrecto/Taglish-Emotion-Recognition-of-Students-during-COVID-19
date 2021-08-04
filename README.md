# Taglish-Emotion-Recognition-of-Students-during-COVID-19
A study that aims to unfold what emotions did Filipino students manifest during a year of Covid-19 quarantines.


## Paper Title & Abstract:
### Emotion Recognition of Students’ Bilingual Tweets during COVID-19 Pandemic using Attention-based Bi-GRU

This paper studied the emotions manifested by students during from March 2020 to April 2021, a year of COVID-19 pandemic. Our tweet compromises of Taglish (Tagalog—English) texts, a low-resource code-switching language. The texts were cleaned and  was translated from Taglish to English. WordNet Affect was used to annotate the text with Happy, Angry, Sad, Surprise, and Fear as the output. A neural network, Bi-GRU with Attention layer was used and was compared to Bernoulli Naïve Bayes (BNB), and Support Vector Machine (SVM) which are commonly used algorithm for Taglish emotion recognition. We applied oversampling with data augmentation using contextual word augmentation. We also applied undersampling to compare and evaluate how the  oversampling method affects the model’s performance. A 100-dimensional GloVe word embedding was applied to the data before training. The augmentation method does not affect the model’s performance negatively instead has helped the Bi-GRU with Attention boost its performance. Bi-GRU with Attention have a higher F1-score on all emotions compared to the other three algorithms but as expected requires large amount of data. The results show that the most dominant emotion manifested by students throughout the year is Surprise immediately followed by Sad and Fear, the three are close in values.
