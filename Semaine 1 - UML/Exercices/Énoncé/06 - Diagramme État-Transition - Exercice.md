## Diagramme État-Transition - Exercice : Transactions de Réservation de Livres

## Contexte :

Dans cet exercice, vous utiliserez vos connaissances sur les diagrammes d'état-transition pour modéliser le cycle de vie
d'une réservation de livre dans un système de bibliothèque en ligne.

## Objectif :

Créer un diagramme état-transition UML qui représente les différents états d'une transaction de réservation de livre et
les transitions déclenchées par des événements dans un système de réservation de bibliothèque.

## Scénario à Modéliser :

Le cycle de vie d'une transaction d'emprunt de livre dans une bibliothèque en ligne comprend plusieurs étapes, depuis la
demande d'emprunt jusqu'à la confirmation. Les transitions suivantes doivent être modélisées :

1. John soumet une demande pour emprunter "Les Misérables".
2. Le système passe à l'état de vérification de la disponibilité du livre.
3. Si le livre est disponible, le système passe à l'état d'enregistrement de l'emprunt.
4. L'emprunt est enregistré, et la transaction passe à l'état de confirmation.
5. John reçoit la confirmation de l'emprunt.

## Instructions :

1. Définissez les États :
    - **DemandeSoumise :** La demande d'emprunt a été soumise par John.
    - **VérificationDisponibilité :** Alice vérifie si le livre est disponible.
    - **EnregistrementEmprunt :** L'emprunt est enregistré dans le système.
    - **ConfirmationEmprunt :** Le système envoie une confirmation à John.
2. Modélisez les Transitions :
    - Transition de **DemandeSoumise** à VérificationDisponibilité lorsque la demande est soumise.
    - Transition de **VérificationDisponibilité** à EnregistrementEmprunt si le livre est disponible.
    - Transition de **EnregistrementEmprunt** à ConfirmationEmprunt lorsque l'emprunt est enregistré.
    - Transition de **ConfirmationEmprunt** à l'état final lorsque John reçoit la confirmation.
3. Utilisez des Guards et des Transitions Conditionnelles :
    - Ajoutez une condition dans l'état **VérificationDisponibilité** pour gérer les cas où le livre n'est pas
      disponible.
      Dans ce cas, la transaction passe à un état EmpruntRefusé.
