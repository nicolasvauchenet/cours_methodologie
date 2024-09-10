# Diagramme de Séquence - Exercice : Distributeur Automatique de Billets (ATM)

## Contexte :

Cet exercice a pour but de modéliser le fonctionnement d'un distributeur automatique de billets (ATM) en utilisant un
diagramme de séquence UML. Vous devez créer un diagramme détaillant les interactions entre un client, un ATM, et les
systèmes d'authentification et de base de données associés.

## Objectif :

Créer un diagramme détaillant les interactions entre un client, un ATM, et les systèmes d'authentification et de base de
données associés.

## Acteurs et Systèmes Impliqués :

- Client : Utilise l'ATM pour effectuer des transactions telles que des retraits ou des dépôts.
- ATM : Appareil qui permet au client d'effectuer des transactions bancaires.
- Authentification : Système qui vérifie l'identité du client, généralement via un code PIN.
- Base de données : Stocke les informations relatives aux comptes, aux transactions, et aux tentatives d'accès.

## Étapes du Processus à Modéliser :

1. Insertion de la Carte :

- Le client introduit sa carte bancaire dans l'ATM.

2. Demande du Code PIN :

- L'ATM demande au client de saisir son code PIN.

3. Saisie du Code PIN :

- Le client entre son code PIN.

4. Vérification du Code PIN (Alternative) :

- Si le code PIN est correct, continuer à l'étape 5.
- Si le code PIN est incorrect, permettre au client jusqu'à 3 tentatives avant de retenir la carte et d'afficher un
  message de fin.

5. Sélection du Type d'Opération :

- L'ATM demande au client de choisir entre plusieurs types d'opérations (retrait, dépôt, consultation de solde, etc.).

6. Exécution de l'Opération (Alternative) :

- Pour un dépôt : permettre au client de déposer de l'argent.
- Pour un retrait : demander le montant et vérifier la disponibilité des fonds avant de distribuer l'argent.

7. Confirmation et Clôture :

- L'ATM confirme la transaction et retourne la carte au client.
