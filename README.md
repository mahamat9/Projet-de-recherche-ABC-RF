# ABC-RF : Approximate Bayesian Computation with Random Forests

Ce dépôt contient les travaux réalisés dans le cadre du projet **ABC-RF** (Approximate Bayesian Computation avec Random Forests) sous l'encadrement de C-E. Rabier(IRHS-LAREMA), visant à estimer des paramètres de modèles statistiques lorsque la vraisemblance est difficile ou impossible à calculer.

## Description

L'approche **ABC-RF** combine l'Approximate Bayesian Computation (ABC) avec des **forêts aléatoires** pour améliorer l'estimation des paramètres à partir de statistiques descriptives. Le projet explore l'utilisation des forêts aléatoires comme estimateurs de la postériorité pour surmonter les limites des méthodes classiques d'ABC.

### Objectifs
- Implémenter la méthode ABC-RF pour l'estimation bayésienne
- Comparer la méthode ABC classique avec ABC-RF
- Évaluer la qualité des estimations sur des modèles simulés(exemple MA1 vs MA2)
- Étudier l'importance des statistiques résumées pour l'estimation des paramètres

## Contenu

- **Simulation de données** : Génération de données synthétiques à partir de modèles simulés
- **Entraînement des forêts aléatoires** pour approximer la postériorité
- **Sélection de statistiques résumées** par importance des variables
- Visualisation des distributions a posteriori
- Comparaison des métriques (erreur quadratique moyenne, biais)

## Prérequis

- R
- Ggplot
- abcrf
- randomforest

