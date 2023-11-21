
Projet d'Analyse des Données de la FAO
Mise en situation
Félicitations pour votre nouveau poste à la FAO ! La mission consiste à effectuer une étude sur la démographie et la nutrition. Avant de commencer, assurez-vous d'avoir acquis ou révisé les concepts principaux de Pandas. Utilisez un environnement dédié à la data science avec un Jupyter Notebook.

Étape 0 : Formation sur Pandas et préparation de l'environnement
Revoir ou apprendre les concepts principaux de Pandas.
Utiliser un Jupyter Notebook pour le projet.
Étape 1 : Récupération des jeux de données
Extraire 3 jeux de données (CSV) de la section FAOSTAT du site de la FAO pour les produits d'origine animale, les produits d'origine végétale, et la population de chaque pays pour les années 2018 et 2019.
Sélectionner les éléments pertinents pour les produits (disponibilité alimentaire en kg, kcal, protéines, matière grasse par personne par jour).
Importer les données avec Pandas et créer 3 DataFrames : df_anim, df_veg, et df_pop.
Créer un répertoire Git local et un répertoire GitHub pour versionner le projet.
Étape 2 : Nettoyage et préparation des données
Nettoyer les titres de colonnes (espaces, majuscules, underscores).
Ajouter une colonne 'type' à df_anim et df_veg avec les valeurs 'animal' et 'vegetal'.
Regrouper df_anim et df_veg en un seul DataFrame product.
Transformer df_pop et product en gardant uniquement les colonnes nécessaires.
Fusionner df_pop avec product et renommer les colonnes conformément aux captures d'écran fournies.
Étape 3 : Exploration
Explorer les types de données, les valeurs manquantes, et détecter les valeurs aberrantes.
Indexer le jeu de données par country_code, country, year, pop_1000_hab, type, et item.
Créer des masques pour afficher un DataFrame contenant seulement l'année 2018.
Télécharger de nouveaux datasets pour ajouter des zones géographiques au jeu de données.
Étape 4 : Synthèse et Présentation du Projet
Introduction

Présenter la problématique choisie et son importance.
Contexte

Donner un aperçu des données et de leur source (FAO) sans entrer dans les détails techniques.
Principaux Résultats

Mettre en avant les découvertes les plus importantes liées à la problématique.
Implications

Discuter de ce que les résultats signifient pour la problématique choisie, par exemple, comment ils influencent la compréhension de la sécurité alimentaire.
Conclusions et Recommandations

Conclure avec une synthèse des points clés et proposer des recommandations ou des pistes d'action.
Conseils pour Rendre la Présentation Engageante
Utiliser des visuels impactants tels que des graphiques et des infographies.
Encourager l'interactivité en invitant les questions et la participation du public.
Intégrer des éléments émotionnels pour créer une connexion avec l'audience.