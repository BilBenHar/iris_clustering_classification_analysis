
-----

### Projet d'analyse des Iris : Clustering et Classification

-----

### 🚀 Vue d'ensemble du projet

Ce projet a pour but d'explorer et de modéliser le célèbre jeu de données des iris. Il met en pratique, sous forme d'exercice simple, deux concepts fondamentaux du machine learning : l'apprentissage non supervisé (**clustering**) et l'apprentissage supervisé (**classification**).

-----

### 📁 Structure du projet

  * **`notebooks/`** : Ce dossier contient les deux notebooks Jupyter du projet.
      * `iris_clustering.ipynb` : Ce notebook effectue une analyse de clustering (K-Means) pour segmenter les espèces et évalue les résultats avec la méthode du coude et le score de silhouette.
      * `iris_classification.ipynb` : Ce notebook réalise une classification supervisée avec un modèle de régression logistique pour prédire les espèces.
  * **`data/`** : Ce dossier contient les fichiers CSV utilisés dans les notebooks.
      * `iris_without_species.csv` : Le jeu de données pour l'exercice de clustering (sans les étiquettes des espèces).
      * `iris_with_species.csv` : Le jeu de données pour vérifier les résultats du clustering et pour l'exercice de classification (contient les étiquettes des espèces).
  * **`requirements.txt`** : Liste des bibliothèques Python nécessaires pour exécuter le projet.
  * **`.gitignore`** : Fichier de configuration pour ignorer les fichiers non pertinents.
  * **`README.md`** : Ce fichier de description.

-----

### ⚙️ Prérequis

Pour exécuter ce projet localement, assurez-vous que les bibliothèques indiquées dans `requirements.txt` sont installées. La méthode la plus simple est d'utiliser `pip` avec le fichier `requirements.txt` inclus.

```bash
pip install -r requirements.txt
```

---- 

### 💾 Données

Le jeu de données des iris est l'un des plus populaires en machine learning. Il est inclus directement dans le dépôt dans le dossier `data/` car sa petite taille le permet. Les données comportent quatre variables numériques : la longueur et la largeur des sépales, et la longueur et la largeur des pétales.

-----

### 📈 Méthodologie et résultats

L'analyse est divisée en deux parties distinctes :

1. **Clustering** : Le premier notebook (`iris_clustering.ipynb`) utilise l'algorithme K-Means pour regrouper les données. Les méthodes du coude et du score de silhouette ont été utilisées pour déterminer le nombre optimal de clusters. Le résultat a été comparé à la véritable classification des espèces.

2. **Classification** : Le second notebook (`iris_classification.ipynb`) traite le problème comme un cas de classification supervisée. Une régression logistique a été utilisée pour prédire l'espèce de chaque fleur. Les résultats de la classification sont évalués à l'aide de métriques de performance standard (classification report et confusion matrix).

----- 

### ✒️ Auteur

**Bilal BEN HAROUAL** - [Profil GitHub](https://github.com/BilBenHar)