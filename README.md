# Classification des billets de blog par tranche d'âge

Le corpus est composé 512629 billets de blogs provenant de trois tranches d'âge.

- 10 à 19 ans : 35.1%
- 20 à 29 ans : 46.9%
- 30 ans et plus : 17.9%

## Prétraitement

Pour prétraiter les données exécutez:

```bash
python preprocess.py <path_to_file_train> <path_to_file_test> <nombre_lignes_a_pretraiter>
```

## Lancer l'entraîner du modèle Bayes Naïf

```bash
python src/Naive_Bayes.py
```

## Classifieur LSTM

Le classifieur LSTM utilisé se trouve en format .ipynb dans le dossier src/.

## Classifieur BERT

Le classifieur BERT utilisé se trouve en format .ipynb dans le dossier src/.

## Auteur

Francis de Ladurantaye
