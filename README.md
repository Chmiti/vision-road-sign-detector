# 🛑 Vision Road Sign Detector

Projet de détection et classification de panneaux de signalisation à l’aide de CNN (PyTorch) et OpenCV.

## 📁 Structure
- `src/` : Scripts d’entraînement, modèle, fonctions utilitaires
- `data/` : Dataset (images et labels, GTSRB par exemple)
- `results/` : Graphiques, confusion matrix, checkpoints
- `inference/` : Code pour tester sur image ou vidéo

## 🛠️ Outils
- Python 3.10
- PyTorch
- OpenCV
- NumPy
- Matplotlib

## 🚀 Objectifs
- Entraîner un modèle CNN sur des images de panneaux routiers
- Évaluer les performances sur le dataset GTSRB
- Détecter les panneaux dans une image ou vidéo en temps réel

- 📥 Télécharger et organiser le dataset GTSRB (German Traffic Sign Recognition Benchmark)
- 🧽 Prétraiter les images : resize, normalisation, conversion des labels
- 🧠 Concevoir un modèle CNN avec PyTorch pour classifier les panneaux
- 🔁 Entraîner le modèle sur les données d’apprentissage, valider sur test
- 📈 Visualiser les performances : courbes accuracy/loss, confusion matrix
- 💾 Sauvegarder le modèle entraîné pour la phase d’inférence
- 🎥 Créer un script de détection temps réel sur image ou webcam avec OpenCV
- 📂 Structurer le projet comme un dépôt pro : `src/`, `data/`, `results/`, `inference/`
- 🧪 Bonus : possibilité de test vidéo ou intégration embarquée (Raspberry Pi, etc.)
