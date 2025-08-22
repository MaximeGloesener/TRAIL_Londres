### Unimodal

#### MRI

- Modele 2D: Resnet, EfficientNet, ViT
- Modele 3D: DenseNet_3D121, torch r3d_18 (modèle pour les vidéos) ? , custom model  (otamane import les modèles directement depuis monai) https://docs.monai.io/en/stable/networks.html, custom cnn


-> pour 2D: entraîner sur les 3 vues différentes pour comparer les 3

-> Benchmarker les modèles par la suite avec métriques

#### Tabular

- xgboost
- mlp version otmane
- transormfer en texte et passer à un llm type clinicalbert

-> voir les colonnes qu'on garde et qu'on jette etc, être d'accord là dessus
-> traitement des données manquantes ? nan ?

### Multimodal

- fusion des encodeurs image + texte
- medclip
- vlm type qwen vl