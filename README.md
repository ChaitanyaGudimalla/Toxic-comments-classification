# Toxic Comments Classification

## Description

### ABSTRACT
Social media has taken over the world in the twenty-first century. Numerous small enterprises are benefiting. On the other hand, there is also a dark side of it. Through this, people are becoming aware of concepts they are unfamiliar with.Few people embrace it positively and work to become accustomed to it, while many misinterpret it and begin spreading toxic comments.Hazardous or toxic remarks are rude, unpleasant, or nonsensical online comments that generally lead other users to quit a conversation.The possibility of online bullying and suffering limits people's divergent opinions, which inhibits the outflow of thoughts.Locales struggle to effectively progress discussions, which forces many networks to restrict or eliminate user comments.Thus, many social media platforms utilize NLP techniques to eliminate such remarks in order to predict their users' behavior.

This project works on the classification of toxic and non-toxic comments in the dataset available on Kaggle.Firstly, defining the toxic comments into six categories namely toxic, severe toxic, obscene, threat, insult, and identity hate. Further, textual data preprocessing techniques are applied to clean and format the data.Therefore, the preprocessed data is fed to deep learning models (LSTM and CNN) to label the comments and to predict the probability of toxic comments.Thus, evaluating the accuracy of the model that predicts the toxicity in the comments.The goal of this project is to accurately identify harmfulness and limit its negative effects, which helps associations take significant action.

### KEYWORDS
- LSTM (Long Short-Term Memory)
- LSTM-CNN (Convolutional Neural Network)
- Text classification
- fastText
- Hyperparameter tuning
- Accuracy

### Theoretical Analysis of Techniques Results
Discussing our initial results, show that both the LSTM and LSTM-CNN models are effective in classifying toxic comments which gave accuracy of 87.7 and 87.1 respectively.However, the LSTM-CNN model outperforms the LSTM based on the results in finding the probability of toxicity in each comment category.We plan to further improve the model's performance by fine-tuning the hyperparameters, exploring other deep learning architectures,and analyzing the misclassified comments to identify the model's weaknesses.

### CONCLUSION
In this project milestone, we presented our approach for classifying toxic comments using LSTM and LSTM-CNN models.Our initial results show promising performance, and we plan to further improve the model's accuracy and robustness.We believe that our project has the potential to contribute to a safer and healthier online community by identifying and preventing online abuse.

## Installation

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/ChaitanyaGudimalla/toxic-comments-classification.git
cd toxic-comments-classification
