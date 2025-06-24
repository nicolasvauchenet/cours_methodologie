# Diagramme de Communication - Exercice : Transactions de Réservation de Livres

## Contexte :

Dans cet exercice, vous utiliserez vos connaissances sur les diagrammes de communication pour modéliser les interactions
entre les objets dans un système de réservation de bibliothèque.

## Objectif :

Créer un diagramme de communication UML qui illustre les interactions entre les objets d'un système de réservation de
bibliothèque en ligne, lors d'une transaction d'emprunt de livre.

## Scénario à Modéliser :

Un lecteur, John Doe, souhaite emprunter le livre "Les Misérables" de Victor Hugo. Un bibliothécaire, Alice Smith,
traite cette demande de réservation. Les interactions suivantes doivent être modélisées :

1. John fait une demande pour emprunter "Les Misérables".
2. Alice vérifie la disponibilité du livre.
3. Le livre est disponible, et Alice enregistre l'emprunt dans le système.
4. John reçoit une confirmation de l'emprunt.

## Instructions :

1. Créez les Objets :
    - Un Lecteur pour John Doe avec ses attributs spécifiques.
    - Un Bibliothécaire pour Alice Smith.
    - Un Livre pour "Les Misérables".
    - Un Emprunt représentant la transaction entre John et la bibliothèque.
2. Modélisez les Interactions :
    - Utilisez des flèches pour montrer les messages échangés entre les objets.
    - John -> Alice : Demande d'emprunt.
    - Alice -> Livre : Vérification de la disponibilité.
    - Alice -> Emprunt : Enregistrement de l'emprunt.
    - Emprunt -> John : Confirmation de l'emprunt.
3. Utilisez des Annotations :
    - Ajoutez des annotations pour préciser les attributs des objets et les messages échangés. Par exemple, spécifiez
      que le livre est disponible avant que l'emprunt soit confirmé.
