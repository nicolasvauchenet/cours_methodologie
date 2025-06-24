## Les méthodes agiles historiques, populaires et utiles

### Introduction aux méthodes agiles

L'agilité n'est pas une méthode unique, mais un ensemble de principes et de pratiques qui se déclinent en différentes
méthodologies. Certaines de ces méthodes sont devenues incontournables dans le développement logiciel, tandis que
d'autres sont plus spécifiques ou moins connues, mais tout aussi utiles selon le contexte. Cette section présente cinq
des méthodes agiles les plus influentes et fréquemment utilisées : **Kanban**, **Scrum**, **Extreme Programming (XP)**,
**Agile Modeling**, et **Crystal**.

### Kanban

#### Qu'est-ce que Kanban ?

**Kanban** est une méthode agile visuelle qui a ses racines dans le système de production de Toyota. Le terme "Kanban"
signifie "carte" ou "panneau" en japonais. Il repose sur la gestion visuelle du flux de travail à l’aide de cartes
représentant les différentes tâches à accomplir. Le tableau Kanban est divisé en plusieurs colonnes représentant l’état
d’avancement des tâches, comme "À faire", "En cours", et "Terminé". L’objectif principal est de limiter le **travail en
cours (WIP)** pour éviter les goulets d'étranglement et maximiser la productivité.

#### Exemple concret d'utilisation de Kanban

Une équipe de développement utilise un tableau Kanban pour gérer les tickets d'assistance technique. Chaque demande de
support est placée dans la colonne "À faire". Lorsqu'un développeur commence à travailler dessus, la carte passe dans la
colonne "En cours", puis dans "En attente de validation" si des vérifications sont nécessaires, et enfin dans "Terminé"
une fois que la demande est résolue. En limitant le nombre de tâches "En cours", l'équipe peut se concentrer sur un
nombre réduit de demandes, réduisant les retards et les risques de confusion.

#### Avantages de Kanban

- Visualisation claire du flux de travail.
- Limitation du travail en cours (WIP), ce qui améliore la productivité.
- Flexibilité : les tâches peuvent être ajoutées ou retirées à tout moment.
- Idéal pour les équipes cherchant à améliorer leur flux de travail existant sans bouleverser leur organisation.

### Scrum

#### Qu'est-ce que Scrum ?

**Scrum** est l'une des méthodes agiles les plus populaires. Introduite par Ken Schwaber et Jeff Sutherland dans les
années 1990, Scrum repose sur des itérations courtes appelées **sprints**, généralement de deux à quatre semaines.
L’équipe Scrum est auto-organisée et comprend trois rôles principaux : le **Scrum Master**, qui facilite le processus
Scrum, le **Product Owner**, responsable du **Product Backlog** (liste des fonctionnalités), et l’équipe de
développement, qui réalise les tâches planifiées.

#### Exemple concret d'utilisation de Scrum

Une équipe de développement travaille sur une application mobile. Le **Product Owner** définit les priorités des
fonctionnalités dans le **Product Backlog**. Lors du **Sprint Planning**, l'équipe sélectionne les **User Stories** les
plus importantes et les planifie pour le prochain sprint de deux semaines. À la fin de chaque sprint, une **revue de
sprint** est organisée pour montrer les fonctionnalités développées et collecter des retours avant de préparer le sprint
suivant.

#### Avantages de Scrum

- Structure claire et répétitive qui facilite la planification à court terme.
- Livraisons fréquentes permettant des retours clients réguliers.
- Amélioration continue à travers les rétrospectives de sprint.
- Favorise la collaboration et la responsabilisation des équipes.

### Extreme Programming (XP)

#### Qu'est-ce que Extreme Programming (XP) ?

**Extreme Programming** (XP) est une méthode agile qui met l'accent sur la qualité du code et la réactivité aux
changements. Développée par Kent Beck, XP repose sur un ensemble de bonnes pratiques techniques, telles que le
**développement piloté par les tests (TDD)**, l’**intégration continue**, le **refactoring**, et le
**pair programming**. XP cherche à réduire les risques et à fournir un produit de haute qualité en livrant de petites
versions incrémentales du logiciel fréquemment.

#### Exemple concret d'utilisation de XP

Dans une équipe développant un nouveau système de gestion d'entrepôts, les développeurs travaillent en binômes (**pair
programming**) pour écrire du code de manière plus collaborative et réduire les erreurs. Avant d’écrire chaque
fonctionnalité, ils créent des tests unitaires qui définissent le comportement attendu du code (**Test-Driven
Development**), puis écrivent le code pour faire passer ces tests. Cela garantit que chaque nouvelle fonctionnalité est
testée et fonctionne correctement avant d'être intégrée dans le projet.

#### Avantages de XP

- Amélioration de la qualité du code grâce à des pratiques techniques rigoureuses.
- Réduction des erreurs grâce à des tests automatisés et à l’intégration continue.
- Collaboration étroite entre les développeurs.
- Capacité à s'adapter rapidement aux changements des exigences.

### Agile Modeling

#### Qu'est-ce que Agile Modeling ?

**Agile Modeling** est une méthode spécifique pour gérer la **modélisation** et la **conception** dans les projets
agiles. Contrairement aux approches traditionnelles où la modélisation peut être lourde et rigide, Agile Modeling prône
des **modèles simples** et **juste suffisants** pour répondre aux besoins du projet à un instant donné. Les équipes
doivent être prêtes à ajuster ou à abandonner des modèles à mesure que le projet évolue.

#### Exemple concret d'utilisation de Agile Modeling

Dans le cadre de la refonte d’un site web, une équipe utilise des **croquis rapides** et des **diagrammes UML légers**
pour concevoir l’architecture de la base de données. Ces modèles sont créés rapidement pour permettre une discussion
entre les développeurs et les parties prenantes. Une fois que le développement commence, ces modèles sont ajustés ou
jetés en fonction des besoins réels du projet.

#### Avantages de Agile Modeling

- Flexibilité dans la conception et la modélisation.
- Permet d’éviter la sur-modélisation et de se concentrer sur les aspects essentiels du projet.
- Encourage une collaboration continue autour des modèles, au lieu de les voir comme des documents figés.

### Crystal

#### Qu'est-ce que Crystal ?

**Crystal** est une famille de méthodologies agiles développée par Alistair Cockburn. Contrairement à d'autres méthodes
rigides, Crystal se distingue par son approche flexible et ajustable en fonction des besoins et des contraintes du
projet. Crystal met l'accent sur la **communication** entre les membres de l'équipe, l'ajustement en fonction de la
taille de l'équipe et du projet, et la réduction des formalités administratives. Crystal est décliné en plusieurs
variantes (Crystal Clear, Crystal Yellow, Crystal Orange, etc.), en fonction de la taille et de la complexité des
projets.

#### Exemple concret d'utilisation de Crystal

Une petite équipe de 5 développeurs travaillant sur une application web adopte **Crystal Clear**, une variante légère de
Crystal adaptée aux petites équipes. L’équipe privilégie la communication orale et les réunions informelles, tout en
réduisant la documentation au minimum. Ils organisent des **revues fréquentes** avec les utilisateurs pour valider les
fonctionnalités clés, tout en ajustant leurs processus en fonction des retours.

#### Avantages de Crystal

- Méthode hautement flexible, adaptable à des équipes de différentes tailles.
- Encouragement à ajuster la méthode en fonction des besoins spécifiques du projet.
- Moins de formalisme, laissant plus de place à la communication informelle.
