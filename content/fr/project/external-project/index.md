---
title: Crypto-prediction
summary: Prédiction du prix des crypto-monnaies.
tags:
  - Python
date: "2022-06-22T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: 

image:
  caption: Photo by CNBC
  focal_point: Smart
  
  
links:
  - icon: github
    icon_pack: fab
    name: View code
    url: https://github.com/BOUGHANMIChaima/Crypto-prediction
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''  
  
---
Il s'agit d'un challenge d'intelligence artificielle auquel j'ai participé sur Kaggle. En s'inspirant du site https://github.com/manthanthakker/BitcoinPrediction, il présente des implémentations d'algorithmes d'apprentissage automatique (Random Forest, régression, etc.) et de réseaux neuronaux récurrents/réseaux à mémoire à long terme pour la prédiction de BitCoin. En outre, dans notre cas, nous avons identifié que le BitCoin est la monnaie la plus importante, car la plupart des autres monnaies numériques suivront de près ses tendances. Il est donc essentiel de disposer d'un modèle de prédiction précis pour le BitCoin dans le cadre du projet.

Après avoir importé les données obtenues de Kaggle à partir de notre base de données, qui contient des informations historiques sur plusieurs crypto-monnaies telles que Bitcoin et Ethereum, je suis passée à l'étape de la préparation et du nettoyage des données.

L'étape suivante consiste à traiter les valeurs manquantes, plutôt dans la différence des intervalles d'horodatage. J'ai commencé par extraire chaque crypto-monnaie avec ses horodatages correspondants, en les visualisant pour mieux détecter les différences, puis en imputant chaque valeur manquante par la moyenne de la valeur avant et de la valeur après.
