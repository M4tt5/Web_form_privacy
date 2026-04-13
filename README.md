# WEB Form Privacy – Projet de démonstration

## Description

Ce projet est une démonstration interactive réalisée dans le cadre de l’analyse d’un article scientifique sur la vie privée dans les formulaires web.

L’objectif est de montrer comment un formulaire web peut être amélioré en intégrant un retour en temps réel sur les risques liés à la divulgation de données personnelles.

Ce prototype illustre une approche appelée "Smart Privacy Form", permettant de sensibiliser les utilisateurs lors de la saisie de leurs informations.

---

## Contexte

Les formulaires web sont largement utilisés pour collecter des données personnelles telles que le nom, l’adresse email, la localisation ou le numéro de téléphone.

Cependant, les utilisateurs ne comprennent pas toujours les implications de ces partages. Cela peut entraîner une exposition excessive des données personnelles.

Ce projet s’inscrit dans une réflexion sur l’amélioration de la transparence et de la compréhension des enjeux de confidentialité dans les interfaces utilisateur.

---

## Fonctionnalités

Le prototype propose deux modes d’utilisation :

### Formulaire standard
- Formulaire classique sans retour utilisateur
- Représente les interfaces actuelles

### Formulaire intelligent
- Affichage d’un score de confidentialité en temps réel
- Indicateur visuel (barre de progression)
- Messages dynamiques expliquant les risques
- Avertissements en cas de combinaison de données sensibles

---

## Système de score

Le score de confidentialité est calculé en fonction des données saisies :

- Données à faible sensibilité (nom, âge) : faible impact
- Données à sensibilité moyenne (email) : impact modéré
- Données à forte sensibilité (localisation, téléphone) : impact élevé

Le score est normalisé entre 0 et 100 et évolue en temps réel.

---

## Objectif de la démonstration

Cette démonstration vise à :

- Illustrer les limites des formulaires classiques
- Montrer l’impact d’un retour utilisateur en temps réel
- Améliorer la compréhension des risques liés à la vie privée
- Proposer une piste concrète d’amélioration des interfaces web

---

## Technologies utilisées

- HTML
- CSS
- JavaScript (vanilla)

Aucune dépendance externe n’est requise.

---

## Utilisation

1. Télécharger ou cloner le projet
2. Ouvrir le fichier `formulaire-confidentialite.html` dans un navigateur
3. Interagir avec le formulaire
4. Basculer entre les modes standard et intelligent

---

## Limites

- Le modèle de score est simplifié
- Aucun test utilisateur réel n’a été réalisé
- Le système ne couvre pas tous les types de données
- La démonstration est volontairement pédagogique

---

## Perspectives d’amélioration

- Intégration de recommandations personnalisées
- Adaptation dynamique selon le contexte utilisateur
- Tests utilisateurs pour évaluer l’efficacité réelle
- Extension à des formulaires complexes

---

## Auteur

Projet réalisé dans le cadre d’un travail académique sur la vie privée et les systèmes interactifs.

