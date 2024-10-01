# Modèle Conceptuel de données - Exercice : Système de réservation de bibliothèque en ligne

## Contexte :

Nous souhaitons modéliser le système d’information d’une bibliothèque qui gère des livres, des emprunts et des membres.

## Étape 1 : Identification des entités

- **Livre :** Les livres disponibles à la bibliothèque. Attributs : ID_Livre, Titre, Auteur, Genre.
- **Membre :** Les membres inscrits à la bibliothèque. Attributs : ID_Membre, Nom, Prénom, Adresse.
- **Emprunt :** Représente un emprunt de livre par un membre. Attributs : ID_Emprunt, Date_Emprunt, Date_Retour.

## Étape 2 : Définition des relations

- Un membre peut emprunter plusieurs livres (relation entre Membre et Emprunt).
- Un livre peut être emprunté par plusieurs membres à des moments différents (relation entre Livre et Emprunt).

## Étape 3 : Définition des cardinalités

- Un membre peut effectuer plusieurs emprunts : cardinalité (1,N) entre Membre et Emprunt.
- Un livre peut être emprunté plusieurs fois, mais à un moment donné, il est emprunté par un seul membre : cardinalité
  (1,N) entre Livre et Emprunt.

## Étape 4 : Représentation graphique

Le MCD devrait représenter les entités "Livre", "Membre", et "Emprunt" avec leurs attributs respectifs, ainsi que les
relations "Emprunte" entre les entités "Livre" et "Membre", avec les cardinalités associées.

- **Entité "Livre" :** Attributs (ID_Livre, Titre, Auteur, Genre)
- **Entité "Membre" :** Attributs (ID_Membre, Nom, Prénom, Adresse)
- **Entité "Emprunt" :** Attributs (ID_Emprunt, Date_Emprunt, Date_Retour)
- **Relation "Emprunte" :**
    - Cardinalité (1,N) entre "Membre" et "Emprunt"
    - Cardinalité (1,N) entre "Livre" et "Emprunt"
