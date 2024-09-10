# Modèle Entité-Relation - Exercice : Système de Gestion Universitaire

## Contexte :

Vous êtes consultant en systèmes d'information et travaillez avec une université pour développer un nouveau système de
gestion universitaire. Ce système doit soutenir plusieurs fonctions clés de l'administration universitaire, aidant à
l'organisation et à la gestion des étudiants, des enseignants, des départements, des salles de classe, et des cours.

## Objectif :

Votre mission est de concevoir un modèle Entité/Relation qui décrira de manière exhaustive la structure de données
nécessaire pour soutenir les fonctionnalités requises par le système de gestion universitaire. Ce modèle doit inclure
les entités pertinentes, leurs attributs, les relations entre ces entités, ainsi que les contraintes d'intégrité et les
cardinalités.

## Fonctionnalités à Modéliser :

1. Gestion des Étudiants :

- Entité pour représenter les étudiants avec des attributs tels que l'ID de l'étudiant, le nom, l'adresse, et le numéro
  de téléphone.
- Associations nécessaires pour lier les étudiants aux cours auxquels ils sont inscrits, ainsi qu'aux départements de
  leur spécialisation.

2. Gestion des Enseignants :

- Entité pour les enseignants comprenant des attributs pour l'ID de l'enseignant, le nom, la spécialisation, et les
  coordonnées.
- Associations pour lier les enseignants aux départements auxquels ils appartiennent et aux cours qu'ils enseignent.

3. Gestion des Départements :

- Entité pour les départements avec des attributs pour l'ID du département, le nom du département, et le directeur du
  département.
- Associations pour lier les départements aux cours qu'ils offrent.

4. Gestion des Salles de Classe :

- Entité pour les salles de classe avec des attributs pour l'ID de la salle, la capacité, l'emplacement, et l'équipement
  disponible.
- Associations pour lier les salles de classe aux cours qui y sont enseignés.

5. Gestion des Cours :

- Entité pour les cours comprenant des attributs tels que le code du cours, le nom du cours, la description, les
  crédits, et le nombre d'heures par semaine.
- Associations pour lier les cours aux étudiants inscrits, aux enseignants qui les dispensent, et aux salles de classe
  où ils se déroulent.
