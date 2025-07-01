
markdown
Copier
Modifier
# 🔍 AED_Diabete - Analyse Exploratoire des Données sur le Diabète

Ce projet a pour objectif d'explorer un ensemble de données médicales concernant le diabète, à l'aide de **Pandas** et **YData Profiling** (anciennement `pandas_profiling`). Il s'inscrit dans un exercice de data science visant à détecter des tendances, corrélations, anomalies et valeurs manquantes dans les données.

## 🗂 Description du dataset

Le dataset contient des mesures médicales collectées auprès de patientes, telles que :

- **Pregnancies** : Nombre de grossesses
- **Glucose** : Taux de glucose dans le sang
- **BloodPressure** : Pression artérielle diastolique
- **SkinThickness** : Épaisseur de la peau
- **Insulin** : Niveau d’insuline
- **BMI** : Indice de masse corporelle
- **DiabetesPedigreeFunction** : Antécédents familiaux de diabète
- **Age** : Âge de la patiente
- **Outcome** : Diagnostic du diabète (0 = Non, 1 = Oui)

## 🔍 Étapes réalisées

### 1. Chargement et analyse initiale des données avec Pandas
- Affichage des premières lignes (`.head()`)
- Statistiques descriptives avec `.describe()`
- Vérification des valeurs nulles et aberrantes

### 2. Profilage avancé avec `ydata-profiling`
- Génération d’un rapport HTML interactif
- Visualisation des distributions
- Analyse de corrélation entre les variables
- Détection de valeurs manquantes et outliers

### 3. Observations clés
- Présence de valeurs nulles dans les colonnes **Glucose**, **Insulin** et **BMI**
- Corrélation notable entre **Glucose** et **Outcome**
- Tendances intéressantes : les patientes avec un taux de glucose élevé ont plus de chances d’avoir un diagnostic positif.

## 🚧 Prochaines étapes
- Imputation ou suppression des valeurs manquantes
- Analyse de l’impact des outliers
- Création d’un modèle de prédiction du diabète (classification)

## 💼 Outils et librairies utilisés
- Python 3.12
- Pandas
- YData Profiling (`ydata-profiling`)
- Jupyter Notebook (via VS Code)
- Git & GitHub

---

## 📂 Structure du projet

AED_Diabete/
│
├── diabetes.csv # Fichier de données
├── AED_Diabete.ipynb # Notebook Jupyter
├── profiling_report.html # Rapport généré par ydata-profiling
└── README.md # Ce fichier

yaml
Copier
Modifier

---

## 👨‍💻 Auteur

**Cheikh Niang**  
Etudiant en Data Science  
📧 cheikhniang159@gmail.com 
📍 Sénégal

---

## 📄 Licence

Ce projet est à but pédagogique uniquement.
