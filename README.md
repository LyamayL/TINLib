# TINLib - Présentation
### 🇫🇷 — Bibliothèque de traitement d'images (C++)
#### Projet d’Introduction à la Programmation Impétative (L1 2025-2026, Université Paris-Saclay, Professeur : Nicolas Thiéry)
Ce projet a été développé dans le cadre du cours d'introduction à la programmation impérative (info111). Le but est de créer une bibliothèque C++ permettant le traitement d'images au format PBM (noir et blanc), PGM (intensité de gris) et PPM (couleur). Le module a été créé en binôme avec un cammarade de ma promotion, en salle de travail à la Bibliothèque Universitaire d'Orsay. Cette bibliothèque C++ permet par exemple de :

- Convertir les images PBM, PGM et PPM en tableau à doubles entrées pour faciliter le traitement,
- Calculer l'inverse des images PBM, PGM et PPM
- Afficher les contours d'une image noir et blanc (filtre de Sobel (SANS NORMALISATION) et Double Seuillage),
- Compresser une image à l'aide de l'algorithme du SuperPixel.
- Des outils permettant de passer du format JPG au format PGM/PBM/PPM et vice-versa

#### Exemples :
Image de Bruce Willis en noir et blanc (format PBM) :
![Bruce Willis en noir et blanc]("images/")

Image Inverse de Bruce Willis : 
![Bruce Willis en blanc et noir]("images/")

Contours de l'image affiché (algorithme de double seuillage) :
![Bruce Willis en noir et blanc avec contours]("images/")
