# Analyse-de-sentiment

Ce projet est réalisé dans le but de s'exercer à l'analyse de sentiment en NLP. Dans ce cadre, j'ai travaillé sur la base de données de Kaggle https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification.
Pour ce faire, j'ai classifer les différents tweets selon trois catégories (Positive, Neutre, Négative) en:
- Nettoyant le corpus (suppression des urls, des caractères spéciaux, des stopwords, lemmatization, suppression des mots avec moins de deux caractères...)
- Visualiser le corpus
- Encodant le corpus (Embeding) avec TF-IDF puis j'ai réalisé une première classification avec un Random Forest. J'ai aussi, essayé l'encodage et la classification avec RoBERTa.

J'ai pu avoir un accuracy autour de 80% sur l'échantillon test avec RoBERTa et un accuracy autour de 70% avec le Random Forest.
