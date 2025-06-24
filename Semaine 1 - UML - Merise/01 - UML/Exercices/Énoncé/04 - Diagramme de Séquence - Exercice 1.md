# Diagramme de Séquence - Exercice : Programmation d'une Conférence

## Contexte :

Une entreprise spécialisée dans l'organisation d'événements corporatifs développe une plateforme en ligne pour gérer
l'ensemble du processus d'organisation d'événements. L'exercice se concentrera sur la création d'une conférence, mettant
en scène les interactions entre l'organisateur, le système de gestion de la plateforme, et le service d'envoi de mails.

## Objectif :

L'objectif est de concevoir un diagramme de séquence UML qui illustre les étapes de la planification d'une conférence
via la plateforme en ligne. Ce diagramme devra montrer clairement la communication entre l'organisateur, le système et
le service d'envoi de mails, ainsi que les décisions prises à chaque étape.

## Acteurs et Systèmes Impliqués :

- Organisateur (Client de l'entreprise) : Initie les demandes de création et de gestion de l'événement.
- Système : Plateforme de gestion d'événements qui traite les demandes de l'organisateur et gère les données des
  participants.
- Service d'Envoi de Mails : Système externe ou intégré qui gère l'envoi de notifications et de confirmations par mail
  aux participants.

## Étapes du Processus à Modéliser :

1. Demande de Création de la Conférence :

- L'organisateur envoie une demande au système pour créer une nouvelle conférence.

2. Obtention de la Liste des Participants :

- Le système récupère et envoie une liste des participants potentiels à l'organisateur.

3. Sélection des Participants :

- L'organisateur sélectionne des participants de la liste et envoie les sélections au système.

4. Envoi des Invitations :

- Le système transmet la liste des participants sélectionnés au service d'envoi de mails.
- Le service d'envoi de mails envoie des invitations aux participants.

5. Réponse des Participants :

- Les participants répondent à l'invitation en confirmant ou déclinant leur présence.
- Le service d'envoi de mails collecte les réponses et les transmet au système.

6. Compilation de la Liste Définitive des Participants :

- Le système compile la liste définitive des participants et leurs horaires de passage.
- Le système envoie cette liste à l'organisateur pour validation.

7. Validation par l'Organisateur :

- L'organisateur valide la liste et les horaires.

8. Confirmation aux Participants :

- Une fois validé, le système demande au service d'envoi de mails de confirmer la participation aux participants
  sélectionnés.
