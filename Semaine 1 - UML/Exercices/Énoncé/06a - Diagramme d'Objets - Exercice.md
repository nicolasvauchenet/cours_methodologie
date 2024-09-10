# Diagramme d'Objets - Exercice : Transactions de Réservation de Livres

## Contexte :

Dans le cadre de votre cours sur UML, nous allons utiliser les connaissances acquises pour visualiser le fonctionnement
pratique d'un système de réservation de bibliothèque à un moment donné. Cet exercice vous permettra de comprendre
comment les objets interagissent entre eux et avec les utilisateurs dans un contexte réel.

## Objectif :

Créer un diagramme d'objets UML qui illustre une série d'interactions typiques au sein d'un système de réservation de
bibliothèque en ligne. Ce diagramme montrera des instances spécifiques de classes et leurs interactions lors d'un
scénario de réservation de livre.

## Scénario à Modéliser :

Imaginez que le lecteur "John Doe" souhaite emprunter le livre "Les Misérables" de Victor Hugo. Le bibliothécaire "Alice
Smith" traite cette transaction. L'exercice consiste à visualiser les objets et les interactions suivants :

1. John fait une demande pour emprunter "Les Misérables".
2. Alice vérifie la disponibilité du livre.
3. Le livre est disponible ; Alice enregistre l'emprunt dans le système.
4. John reçoit une confirmation de l'emprunt.

## Instructions :

### Créez des Instances de Classes :

- Un objet Lecteur pour John Doe avec ses attributs spécifiques.
- Un objet Bibliothécaire pour Alice Smith.
- Un objet Livre pour "Les Misérables".
- Un objet Emprunt représentant la transaction entre John et la bibliothèque.

### Définissez les Attributs :

Pour chaque objet, spécifiez les valeurs des attributs comme le nom, l'identifiant, l'email pour John et Alice, le titre
et l'auteur pour le livre, ainsi que les dates pertinentes pour l'emprunt.

### Modélisez les Interactions :

Utilisez des flèches pour montrer les interactions entre John, Alice, et le livre à travers l'objet Emprunt. Par
exemple, John demande à emprunter, Alice vérifie et enregistre l'emprunt, etc.

### Utilisez des Liens et des Annotations :

Indiquez clairement les associations, les messages passés entre les objets, et tout autre détail pertinent comme les
actions (méthodes) exécutées par chaque objet.

### Présentez les Multiplicités si Nécessaire :

Montrez comment les objets peuvent interagir avec plusieurs instances d'autres classes si applicable dans votre
scénario.
