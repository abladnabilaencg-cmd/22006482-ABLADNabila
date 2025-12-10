
# 📘 COMPTE RENDU DATA SCIENCE — VERSION MARKDOWN

## 1. Contexte Métier et Mission  
Analyse appliquée au dataset Amazon Sales (fichier DS1_ABLAD).

### Problème (Business Case)
L’objectif est de comprendre les dynamiques du catalogue produit Amazon : structure des produits, prix, promotions, catégories et retours clients.  
Enjeux :
- Identifier les patterns de prix et de réduction.  
- Comprendre la qualité perçue via les avis et notes.  
- Détecter les produits potentiellement problématiques.

## 2. Jeux de Données (Input)
Dataset chargé : **Amazon Sales Dataset**  
- **Taille :** 1465 lignes × 16 colonnes  
- **Colonnes clés :** produit, prix réduit, prix réel, catégorie, note, avis, identifiants utilisateurs.  
- **Type de tâche :** Analyse descriptive + pré-traitement.

## 3. Code Python Utilisé – Laboratoire
Voir notebook source (DS1_ABLAD.ipynb).  
Chargement, inspection et visualisation de df.

## 4. Data Wrangling (Nettoyage)
- Variables prix = chaînes → nécessitent conversion numérique.  
- Colonnes multi-valeurs (ex. user_id, user_name) → nécessitent parsing voire normalisation.  
- Colonnes textuelles longues → NLP possible.

## 5. Exploration (EDA)
Exemples de pistes :
- Distribution des prix / pourcentages de réduction.  
- Popularité par catégorie.  
- Analyse des notes et avis (sentiment).  

## 6. Méthodologie : Split / Préparation
Non applicable directement (pas de modèle ML dans ce notebook), mais nécessaire si ML ajouté :
- Nettoyage → Feature engineering → Split → Modèle.

## 7. Focus Théorique : Algorithmes
Applicable si construction d’un modèle de recommandation ou de scoring (Random Forest, NLP-based models).

## 8. Évaluation
À développer si un modèle est entraîné (classification / régression / clustering).

## Conclusion
Le dataset Amazon permet un large éventail d’analyses : prix, promotions, satisfaction client, structure du catalogue.  
Le rapport suit l’ossature théorique d’un projet Data Science complet.
