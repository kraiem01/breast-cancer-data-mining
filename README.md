# breast-cancer-data-mining
Ce projet explore un ensemble de données génomiques lié au cancer du sein à l’aide de techniques de fouille de données (Data Mining), d’analyse en composantes principales (ACP), de méthodes de réduction de dimension (t-SNE, UMAP), de clustering (CAH, K-means, DBSCAN) ainsi que de classification supervisée (Random Forest, Logistic Regression, etc.).

### Dataset

- 📊 1016 échantillons de cancer du sein
- 🧪 50 niveaux d'expression génique par échantillon
- 🧬 Une étiquette `pam50` indiquant le sous-type moléculaire :
  - **Luminal-A**
  - **Luminal-B**
  - **HER2-enriched**
  - **Basal-like**

### Techniques utilisées

- **Nettoyage des données** : traitement des doublons, valeurs nulles, standardisation
- **Analyse exploratoire** : statistiques descriptives, heatmap de corrélation, boxplots
- **Réduction de dimension** :
  - PCA (Analyse en Composantes Principales)
  - t-SNE
  - UMAP (2D et 3D)
- **Clustering non supervisé** :
  - CAH (Classification Ascendante Hiérarchique)
  - K-means (avec inertie & silhouette)
  - DBSCAN (avec graphe k-distance)
- **Classification supervisée** :
  - Régression Logistique
  - Arbre de Décision
  - Random Forest
  - Équilibrage des classes (undersampling & oversampling)

### Résultats attendus

- Visualisation des sous-types moléculaires dans les différents espaces réduits
- Clustering non supervisé comparé aux sous-types réels
- Évaluation des performances des modèles de classification via :
  - Accuracy
  - Precision
  - Recall
  - F1-Score

### Librairies principales

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `umap-learn`, `imblearn`
- `scipy`, `mpl_toolkits.mplot3d`


### Remarques
Ce projet montre comment appliquer une démarche de Data Mining complète sur un jeu de données biologiques réels. Il peut servir de base à d'autres analyses biomédicales ou à des projets en apprentissage automatique sur des données génétiques.

