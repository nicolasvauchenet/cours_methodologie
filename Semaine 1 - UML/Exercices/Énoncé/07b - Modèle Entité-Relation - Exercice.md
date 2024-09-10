# Modèle Entité-Relation - Exercice : Plateforme de Gestion d'Événements

## Contexte :

Vous travaillez pour une entreprise qui développe une plateforme en ligne destinée à la gestion d'événements
corporatifs. Cette plateforme permet aux utilisateurs de planifier, coordonner et exécuter différents types
d'événements, tels que les conférences, les séminaires, les retraites d'entreprise et les fêtes de fin d'année.

## Objectif :

Votre mission est de concevoir un modèle Entité/Relation qui décrit la structure de données nécessaire pour supporter
les fonctionnalités de la plateforme. Ce modèle devra inclure toutes les entités nécessaires, leurs attributs, les
associations entre elles, et les contraintes d'intégrité correspondantes. Le modèle doit capturer les relations
complexes entre les différents aspects de la gestion d'événements et servir de fondement pour la création de la base de
données sous-jacente.

## Fonctionnalités à Modéliser :

1. Planification d'Événements :

- Entités pour gérer les événements avec des attributs pour la date, le type d'événement, et le statut.
- Associations nécessaires pour lier les événements aux lieux, participants, et autres aspects pertinents.

2. Gestion et Réservation de Lieux :

- Entités pour les lieux avec des attributs pour le nom, l'adresse, et la capacité.
- Associations pour relier les événements aux lieux réservés.

3. Gestion des Participants et des Inscriptions :

- Entités pour les participants avec des attributs pour les informations de contact et le statut d'inscription.
- Entités pour gérer la participation des participants aux événements, avec des attributs pour enregistrer les détails
  spécifiques à chaque participation et le statut.
- Associations pour relier les participants aux événements auxquels ils s'inscrivent.

4. Outils de Communication :

- Entités pour la gestion des communications, incluant les messages envoyés et reçus.
- Associations pour lier les messages aux événements et aux participants.

5. Gestion Budgétaire et Facturation :

- Entités pour la gestion budgétaire avec des attributs pour les budgets prévisionnels, les dépenses réelles, et les
  rapports financiers.
- Associations pour relier les budgets aux événements correspondants.

6. Feedback et Évaluation Post-Événement :

- Entités pour les évaluations avec des attributs pour les retours des participants et les analyses de performance.
- Associations pour relier les évaluations aux événements évalués.
