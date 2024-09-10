# Modèle Logique de Données - Exercice : Système de gestion de réservation de chambres d'hôtel

## Contexte :

Nous souhaitons modéliser un système de réservation pour un hôtel qui gère les chambres, les clients et les
réservations.

## MCD fourni :

- **Chambre :** Attributs (ID_Chambre, Numéro_Chambre, Type_Chambre, Prix).
- **Client :** Attributs (ID_Client, Nom, Prénom, Email).
- **Réservation :** Attributs (ID_Réservation, Date_Début, Date_Fin).
- **Relations :**
    - Un client peut effectuer plusieurs réservations, mais une réservation ne concerne qu'un seul client.
    - Une chambre peut être réservée plusieurs fois, mais une réservation concerne une seule chambre.

## Étape 1 : Conversion des entités en tables

- **Table Chambre :** ID_Chambre (PK), Numéro_Chambre, Type_Chambre, Prix.
- **Table Client :** ID_Client (PK), Nom, Prénom, Email.
- **Table Réservation :** ID_Réservation (PK), Date_Début, Date_Fin.

## Étape 2 : Conversion des relations en clés étrangères

- Dans la table Réservation :
    - Clé étrangère ID_Client (FK) pour établir la relation avec la table "Client".
    - Clé étrangère ID_Chambre (FK) pour établir la relation avec la table "Chambre".

## Étape 3 : Définition des clés primaires

- Clé primaire pour la table Chambre : ID_Chambre.
- Clé primaire pour la table Client : ID_Client.
- Clé primaire pour la table Réservation : ID_Réservation.

## Étape 4 : Ajout des contraintes d'intégrité

- Dans la table Réservation, les champs ID_Client et ID_Chambre ne peuvent pas être NULL, car chaque réservation doit
  obligatoirement concerner un client et une chambre.
- Les relations entre Client et Réservation, ainsi qu'entre Chambre et Réservation, sont traduites par des clés
  étrangères avec des contraintes d'intégrité référentielle (les clients et les chambres doivent exister pour que la
  réservation soit valide).
