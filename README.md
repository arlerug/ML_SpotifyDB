# Spotify DB: Progetto Machine Learning and Data Analysis 

## Descrizione
Questo progetto è stato realizzato per l'esame di Machine Learning and Data Analysis. Si concentra sull'analisi dei brani musicali utilizzando il dataset "Ultimate Spotify Tracks DB", disponibile su Kaggle ([link al dataset](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db?select=SpotifyFeatures.csv)). 
L'obiettivo principale è esplorare le caratteristiche delle tracce, rilevare outlier e sviluppare modelli di machine learning per la classificazione dei generi musicali.

## Dataset
Il dataset include informazioni su tracce musicali di diversi generi, con feature numeriche relative a caratteristiche musicali, metriche di popolarità e metadati.

## Analisi e Preprocessing
- Visualizzazione dei dati: Grafici boxplot per rilevare outlier nelle feature
- Preprocessing:
  - Rimozione di valori anomali
  - Normalizzazione delle feature
  - Encoding delle variabili categoriche (es. `genre`)

## Modelli di Machine Learning
Abbiamo testato diversi modelli per la classificazione dei generi musicali:
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP) (Problemi con dati non numerici, risolti con Label Encoding)

Metriche di valutazione:
- Accuracy
- F1-score (macro e weighted)
- Classification Report

## Visualizzazioni
- Boxplot delle feature per individuare gli outlier
- Grafici di distribuzione dei generi
- Matrice di confusione per i modelli

## Tecnologie Utilizzate
- Python
- Scikit-learn (per il machine learning)
- Matplotlib & Seaborn (per la visualizzazione)
- Pandas & NumPy (per la gestione dei dati)

---
Autore: Alessandra Ruggeri  
Contatti: alessandra.ruggeri@studenti.unipg.it

