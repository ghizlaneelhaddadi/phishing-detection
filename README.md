#  Système de détection des attaques de phishing par e-mail

Ce projet consiste à développer un **système de détection des attaques de phishing par e-mail** basé sur l’apprentissage automatique et le traitement automatique du langage naturel (NLP).  
Il vise à analyser le contenu des e-mails afin de déterminer automatiquement s’ils sont **légitimes** ou **phishing**.

Le système réalise un prétraitement des textes, une extraction de caractéristiques avancée et l’entraînement de modèles Machine Learning / Deep Learning pour améliorer les performances de classification.

##  Méthodologie

###  Prétraitement NLP
- Nettoyage du texte
- Tokenisation
- Suppression des stop words
- Lemmatisation / Stemming

###  Extraction des caractéristiques
- **TF-IDF**
- **Word2Vec**
- **Bag-of-Words**
- Représentations vectorielles de texte

###  Modèles utilisés
- **MLP**
- **SVM**
- **RNN**
- **Gradient boosting**
- **KNN**

## Jeux de données

Les e-mails sont divisés en deux classes :

- 🟢 E-mails légitimes  (enron dataset)
- 🔴 E-mails frauduleux (josé nazario dataset)

## Technologies utilisées

- Python
- Scikit-learn
- TensorFlow
- Pandas
- NumPy
- NLTK / SpaCy
- Matplotlib / Seaborn


