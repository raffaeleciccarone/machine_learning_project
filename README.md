# 🎵 Spotify Hit Predictor: The "From Here" Project

Progetto personale di **Machine Learning** per predire la popolarità dei brani musicali basandosi sulle loro caratteristiche audio, utilizzando un modello **XGBoost Regressor** con Grid Search per l'ottimizzazione degli iperparametri.

![Logo app](img/post_linkedin.png)

> **Quando il Math Rock incontra la Data Science.**

## 🎯 Obiettivo

Predire il valore di **popolarità** (scala 0–100) di un brano a partita dalle sue proprietà audio estratte dalla piattaforma Spotify, come acusticità, loudness, valenza ed altre.

## 📂 Il Dataset
- **Fonte:** Spotify Tracks DB
- **Dimensione:** ~586.000 righe, 20 colonne
- **Features:** Include metriche tecniche come `acousticness`, `danceability`, `energy`, `instrumentalness`, `loudness`, `speechiness`, `tempo` e `valence`.

## 🛠 Tech Stack
Il progetto è stato sviluppato interamente in Python all'interno di un Jupyter Notebook.
* **Data Manipulation:** `Pandas`, `Numpy`
* **Visualization:** `Seaborn`, `Matplotlib` (perché anche l'occhio vuole la sua parte)
* **Machine Learning:** `Scikit-learn`
* **Persistenza:** `Joblib`

## 🤖 Modello: XGBoost Regressor

Il modello è stato ottimizzato tramite **Grid Search** con cross-validation per trovare la combinazione migliore degli iperparametri.

---
## 🎧 About the Music
Tutto questo studio è stato fatto per **"from here"**, il mio brano Math Rock.
Ho usato i dati per comporre? No.
Ho usato i dati per capire come sopravvivere nella giungla dello streaming? Esatto.

---

**"Sono stanco capo 🫠"** - Cit. dal Notebook
Progetto personale — developed as a learning exercise in machine learning and data science.