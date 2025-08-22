### Unimodal

#### MRI

- Modele 2D: Resnet, EfficientNet, ViT
- Modele 3D: DenseNet_3D121, torch r3d_18 (modèle pour les vidéos) ? , custom model  (otmane import les modèles directement depuis monai) https://docs.monai.io/en/stable/networks.html, custom cnn


-> pour 2D: entraîner sur les 2 vues différentes pour comparer les 2 (coronale et axiale; pas de sens de faire sur la vue sagitale)

-> Benchmarker les modèles par la suite avec métriques

#### Tabular

- xgboost
- mlp version otmane
- transformer en texte et passer à un llm type clinicalbert

-> voir les colonnes qu'on garde et qu'on jette etc, être d'accord là dessus
-> traitement des données manquantes ? nan ?
-> voir testing.ipynb de otmane, utilisation de pycare

### Multimodal

- fusion des encodeurs image + texte
- medclip
- vlm type qwen vl
