# Modèle Conceptuel de Données - Exercice : Plateforme de Gestion d'Événements

## Contexte :

Vous travaillez pour une entreprise qui développe une plateforme en ligne destinée à la gestion d'événements
corporatifs. Cette plateforme permet aux utilisateurs de planifier, coordonner et exécuter différents types
d'événements, tels que des conférences, des séminaires, des retraites d'entreprise et des fêtes de fin d'année.

## Objectif :

Concevoir un Modèle Conceptuel de Données (MCD) qui décrit la structure de données nécessaire pour la plateforme de
gestion d'événements. Ce modèle servira de fondement pour la création de la base de données et doit représenter toutes
les entités et relations pertinentes pour les fonctionnalités de la plateforme.

## Éléments à Représenter :

1. Événements :

    - Représentez les événements organisés sur la plateforme.
    - Assurez-vous de modéliser les informations liées à la planification, telles que la date, le type d'événement et le
      statut.

2. Lieux :

    - Les événements se déroulent dans des lieux spécifiques.
    - Représentez les lieux et incluez des informations comme le nom, l'adresse et la capacité.

3. Participants :

    - Les utilisateurs de la plateforme peuvent participer aux événements.
    - Modélisez les participants et les informations liées à leur inscription et leur participation aux événements.

4. Inscriptions :

    - Les participants s'inscrivent à des événements.
    - Représentez les inscriptions et les informations associées à la participation d'un participant à un événement.

5. Messages :

    - La plateforme permet aux participants et aux organisateurs d'échanger des messages concernant les événements.
    - Modélisez les messages et leur lien avec les événements et les participants.

6. Budgets :

    - Chaque événement a un budget pour gérer les dépenses et les recettes.
    - Représentez les budgets associés aux événements et les informations liées à la gestion financière.

7. Évaluations :

    - Après chaque événement, les participants peuvent soumettre des évaluations.
    - Modélisez les évaluations des événements par les participants.

## Contraintes :

- Chaque entité doit avoir des attributs pertinents pour son rôle dans le système (par exemple, un événement a une date
  et un type).
- Les relations entre les entités doivent être modélisées avec les cardinalités appropriées.
- Assurez-vous que votre modèle respecte les contraintes d'intégrité (par exemple, un événement ne peut pas exister sans
  lieu).

## Livrable Attendu :

Vous devez rendre un MCD complet avec les entités, les attributs, les associations et les cardinalités nécessaires à la
gestion de la plateforme d'événements. Ce modèle servira de base pour la conception d'une base de données relationnelle.
