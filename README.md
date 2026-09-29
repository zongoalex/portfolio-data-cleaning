# Portfolio — Data Cleaning with Python & Pandas

## 📌 Projet 1 : Customer Data Cleaning

Nettoyage d'un dataset client brut contenant des anomalies réalistes.

### 🎯 Objectif
Démontrer un pipeline complet : Inspection → Diagnostic → Nettoyage → Validation → Export.

### 📊 Résultats
| Métrique | Avant | Après |
|---|---|---|
| Lignes | 8 | 7 |
| Doublons | 1 | 0 |
| Âges aberrants | 3 | 0 |
| Valeurs manquantes | 3 | 2 |

### 🛠️ Stack
Python · Pandas · Regex · Jupyter

### 📂 Fichiers
- `notebooks/customer_data_cleaning.ipynb` — pipeline complet
- `data/raw/` — données brutes
- `data/cleaned/` — données nettoyées

### 🚀 Reproduire
\`\`\`bash
pip install pandas jupyter
jupyter notebook notebooks/customer_data_cleaning.ipynb
\`\`\`
