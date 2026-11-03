# 📊 TP Statistique & Probabilités avec Python (Tips & Analyse de Données)

Ce dépôt contient les travaux pratiques (TP) réalisés dans le cadre du module de **Statistique**. L'objectif principal est de manipuler, analyser et visualiser des jeux de données statistiques à l'aide de Python (Pandas, Seaborn, Matplotlib, NumPy, SciPy) et d'Excel, notamment en appliquant des méthodes de détection des valeurs aberrantes (Outliers) et de normalisation.

---

## 👤 Auteur

- **Nom & Prénom :** Mohamed BEN ALI
- **Spécialité :** Data Analyst & Intelligence Artificielle (DSIA)
- **Date de création :** 16 Octobre 2026
- **Date de publication :** 3 Novembre 2026

---

## 🌐 Liens & Profils Professionnels

Retrouvez mes travaux, mon parcours et mes projets sur mes différentes plateformes :

- 💼 **LinkedIn :** [Mohamed BEN ALI](https://www.linkedin.com/in/mohamed-ben-ali-m)
- 🐙 **GitHub :** [mohammedbenali4321-a11y](https://github.com/mohammedbenali4321-a11y)
- 🗺️ **Roadmap.sh :** [benalimohamed](https://roadmap.sh/u/benalimohamed)
- 🏆 **Kaggle :** [Mohamed BEN ALI](https://www.kaggle.com/mbaitri)

---

## 🛠️ Technologies & Outils Utilisés

* **Langage :** Python 3.x
* **Environnement de développement :** VS Code / Jupyter Notebook
* **Bibliothèques Python :**
  * `pandas` : Manipulation et analyse de données.
  * `numpy` : Calculs numériques et statistiques.
  * `matplotlib` & `seaborn` : Visualisation de données et graphiques.
  * `scipy` : Calculs statistiques avancés (distribution normale, Z-score).
* **Autres outils :** Microsoft Excel (Formules statistiques FR/EN).

---

## 📋 Sommaire des Exercices

### 🔹 Exercice 1 : Analyse descriptive du Dataset `Tips` (Seaborn)
- Chargement du jeu de données classique `tips`.
- Calcul des indicateurs de tendance centrale (Moyenne, Médiane, Mode) et de dispersion (Plage, Variance, Écart-type) sur `total_bill`.
- Calcul et interprétation des quartiles et centiles ($Q_1$, $D_5$, $C_{95}$) sur la variable `tip`.
- Visualisation de la relation `total_bill` vs `tip` via un `scatterplot` avec lignes de repères statistiques.

### 🔹 Exercice 2 : Mesures statistiques sous Excel
- Calcul des mesures de dispersion et de position sur une série d'âges de participants.
- Utilisation des formules Excel en français (`ECARTYPE.PEARSON`, `QUARTILE.INCLURE`, `CENTILE.INCLURE`, etc.) et en anglais.

### 🔹 Exercice 3 : Détection d'Outliers par la méthode des $2\sigma$ (2 Écarts-types)
- Implémentation en Python de la règle des deux écarts-types ($\mu \pm 2\sigma$).
- Identification automatique des valeurs aberrantes dans un jeu de données de test de certification.
- Tracé graphique avec lignes horizontales (`plt.axhline`) repérant la moyenne et les seuils de tolérance.

### 🔹 Exercice 4 : Détection d'Outliers par les méthodes IQR & Tukey
- Calcul de l'Espace Interquartile ($IQR = Q_3 - Q_1$).
- Définition des seuils de détection IQR ($Q_1 - 1.5 \times IQR$ / $Q_3 + 1.5 \times IQR$) et de Tukey ($Q_1 - 3 \times IQR$ / $Q_3 + 3 \times IQR$).
- Filtrage des données correctes (`data_correct`) en éliminant les Outliers via `np.isin`.
- Visualisation comparative des seuils et mise en évidence des valeurs aberrantes en couleur.

### 🔹 Exercice 5 : Distribution Normale, Z-Score et Normalisation
- Génération d'une distribution normale de 1000 valeurs ($\mu = 50$, $\sigma = 10$).
- Calcul des Z-scores et identification des valeurs hors de l'intervalle $[-3, 3]$.
- Standardisation vs Normalisation Min-Max dans l'intervalle $[0, 1]$.
- Représentation par histogrammes des données brutes, z-scores et données normalisées.

---
