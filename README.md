# Cnn_AlexNet
🧠 Classification de pièces avec CNN (PyTorch)

📌 Description du projet

Ce projet implémente un modèle de réseau de neurones convolutionnel
(CNN) pour la classification d’images de pièces.

Objectifs : - Charger et prétraiter des images - Construire un modèle
CNN - Entraîner et évaluer le modèle - Générer des prédictions

📂 Structure

data/ train/ test/ train.csv tp_cnn_2.ipynb

⚙️ Technologies

-   Python
-   PyTorch
-   Torchvision
-   NumPy, Pandas
-   Matplotlib

📊 Pipeline

1.  Chargement des données
2.  Création du Dataset personnalisé
3.  Split train/validation
4.  DataLoader
5.  Modèle CNN
6.  Entraînement
7.  Évaluation
8.  Prédictions

🧠 Modèle

CNN avec : - Convolutions - Pooling - Fully connected layers

🎯 Entraînement

-   Loss : CrossEntropyLoss
-   Optimizer : SGD

🚀 Améliorations

-   GPU (CUDA)
-   Data augmentation
-   Modèles pré-entraînés
-   Hyperparameter tuning

⚠️ Attention

-   Ordre des images important
-   Gestion des erreurs dataset
