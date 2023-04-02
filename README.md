# SignActionInterpreter
# Décodeur d'actions du langage des signes

Ce projet permet de détecter et de décoder des actions de la langue des signes en utilisant des modèles de détection d'actions et de points clés. Les modèles utilisés sont basés sur Tensorflow et Keras, et construits avec des couches LSTM pour gérer les séquences de points clés.

## Comment ça marche

Le projet est divisé en plusieurs étapes :

1. Extraction des points clés de MediaPipe Holistic
2. Construction d'un modèle de langue des signes en utilisant une détection d'actions basée sur des couches LSTM
3. Prédiction des actions de la langue des signes en temps réel à partir de séquences vidéo

### Installation et importation des dépendances

Le projet nécessite l'installation des bibliothèques suivantes :

- tensorflow
- matplotlib
- mediapipe
- opencv-python

### Détection des points clés
### Extraction des points clés
### Collecte des données
### Prétraitement des données et création des étiquettes
### Construction et entraînement du réseau neuronal LSTM
### Prédictions
### Enregistrement du modèle
### Évaluation
### Test en temps réel