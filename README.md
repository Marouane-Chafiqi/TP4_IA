# TP4:

Salut, je suis Marouane Chafiqi, étudiant en master TEE.

Ce projet est mon quatrième TP d'Introduction à l'Intelligence Artificielle. J'y ai appris à découvrir des groupes cachés dans des données sans donner de réponses au modèle.

## Ce que j'ai fait

1. **Chargement des données** : le jeu de données Iris, sans utiliser les étiquettes
2. **Prétraitement** : vérification des valeurs manquantes et normalisation avec `StandardScaler`
3. **Visualisation** : scatter plot 2D pour repérer les regroupements
4. **K-Means** : regroupement des données en 3 clusters avec scikit-learn
5. **Évaluation** : visualisation des clusters colorés et calcul du silhouette score
6. **Expérimentations** : changement de la valeur de `k` et comparaison avec et sans normalisation
7. **Analyse** : comparaison des clusters avec les classes réelles et choix de `k` avec la méthode du coude

## Ce que j'ai retenu

- Les clusters ressemblent aux vraies classes, mais ne correspondent pas à 100 % : setosa est bien séparée, versicolor et virginica se mélangent un peu.
- La normalisation est importante, car K-Means calcule des distances et une variable avec de grandes valeurs peut dominer les autres.
- La méthode du coude aide à choisir `k` : on cherche le point où l'inertie arrête de baisser vite.

## Outils utilisés

Python, Jupyter Notebook, scikit-learn, pandas, matplotlib

## Fichier principal

`TP4_NLP.ipynb` : le notebook avec le code, les graphiques et mes réponses aux questions.

## Pour le lancer

```
pip install scikit-learn pandas matplotlib
jupyter notebook
```
