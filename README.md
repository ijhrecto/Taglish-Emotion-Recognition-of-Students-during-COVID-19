# Taglish-Emotion-Recognition-of-Students-during-COVID-19
A study that aims to unfold what emotions did Filipino students manifest during a year of Covid-19 quarantines.
## Data and Preprocessing
- taken from tweeter with keywords relating to words such as 'aral'(study), 'school', 'online class', 'COVID-19' which consists of Taglish (tagalog-english) tweets.
- clean tweets -> translate
- annotate the emotions
- two sampling methods: oversampling with text augmentation, and undersampling
## Models
- 100-d Glove word embedding
- Support Vector Machine, Bernoulli Naïve Bayes, and Bi-directional Gated Recurrent Unit with Attention mechanism
- compares SVM and BNB (commonly used algorithm for Tagalog Emotion Recognition) to a Neural network with attention mechanism
- experiment on the two sampling strategy with the three models

