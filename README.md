#  Classification d'Images avec CNN - Détection d'Infections  

##  Introduction  

Ce projet porte sur la **classification d’images** à l’aide de **réseaux de neurones convolutifs (CNN)**, dans le but d’identifier si une image appartient à une **classe infectée ou non infectée**. L’objectif est d’entraîner différents modèles de deep learning pour comparer leurs performances et identifier le modèle le plus performant pour cette tâche.  

Nous avons travaillé avec **trois approches différentes** :  
1.  **Un modèle CNN entraîné from scratch** (construit sans modèle pré-entraîné).  
2.  **Un modèle basé sur VGG16** avec fine-tuning.  
3.  **Un modèle basé sur ResNet50**, également ajusté pour notre dataset.  

Les modèles ont été entraînés sur un dataset d’images contenant deux classes distinctes, et évalués en fonction de plusieurs métriques de classification :  
-  **Accuracy** : Précision globale du modèle  
-  **Precision** : Taux de bonnes prédictions par classe  
-  **Recall (Sensibilité)** : Capacité à détecter les cas positifs  
-  **F1-score** : Équilibre entre précision et recall  
-  **AUC-ROC** : Capacité à distinguer les classes  

Les résultats sont visualisés à l’aide de **matrices de confusion** et de **courbes ROC**, permettant d’analyser la robustesse et la fiabilité de chaque modèle.  

Ce projet est une **première approche** du deep learning appliqué à la classification d’images et vise à comprendre **les avantages et inconvénients des architectures CNN pré-entraînées et celles développées from scratch**.  

 **Objectif final : choisir le meilleur modèle et optimiser ses performances pour une utilisation future.**  
