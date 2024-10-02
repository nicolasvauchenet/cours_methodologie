## Focus sur Agile Modeling

### Qu'est-ce que Agile Modeling ?

**Agile Modeling** est une méthodologie qui fournit des pratiques et des principes pour la **modélisation** et la
**documentation** dans les projets agiles. Contrairement aux approches traditionnelles de modélisation, souvent lourdes
et rigides, Agile Modeling prône une approche légère, flexible et collaborative. L'objectif est de créer des modèles
"juste suffisants" pour soutenir le développement sans tomber dans une sur-modélisation qui ralentirait le processus.

Agile Modeling se concentre sur le fait que les modèles ne sont pas des objectifs finaux, mais des outils pour faciliter
la compréhension et la collaboration. Ils doivent être simples, utiles et facilement modifiables.

### Les principes de base d'Agile Modeling

#### Just Enough (Juste Suffisant)

L'un des principes clés d'Agile Modeling est de créer des modèles qui sont **"juste suffisants"** pour répondre aux
besoins actuels du projet. Il n'est pas nécessaire de passer des jours à créer des modèles détaillés si de simples
croquis ou diagrammes peuvent répondre aux besoins. L'accent est mis sur la **pragmatisme** et la rapidité plutôt que
sur la perfection et la complétude.

- **Exemple concret** : Lors de la conception d'une nouvelle fonctionnalité pour une application de gestion de tâches,
  l'équipe utilise un simple diagramme de flux pour visualiser les étapes clés de la fonctionnalité. Ce croquis permet à
  l'équipe de bien comprendre le fonctionnement attendu sans passer par la création d'un diagramme UML complet et
  détaillé.

#### Good Enough (Suffisamment Bon)

Le principe **Good Enough** signifie que les modèles et les diagrammes n'ont pas besoin d'être parfaits ou exhaustifs,
mais **suffisamment bons** pour atteindre l'objectif. Ils doivent fournir juste assez de détails pour soutenir le
développement et la prise de décision, tout en restant faciles à comprendre et à ajuster si nécessaire.

- **Exemple concret** : Au lieu de créer une documentation technique exhaustive pour une base de données complexe, une
  équipe de développement se contente de créer un schéma simple des tables principales et de leurs relations. Ce modèle
  est "suffisamment bon" pour que les développeurs puissent avancer rapidement dans le développement, et il pourra être
  affiné ou complété plus tard si besoin.

#### Embrace Change (Accepter le changement)

Dans Agile Modeling, les modèles sont considérés comme des **outils vivants**, sujets à être modifiés et ajustés au fur
et à mesure que le projet évolue. L'équipe doit être prête à abandonner ou à adapter les modèles si de nouvelles
informations ou exigences émergent. Il n'est pas nécessaire de conserver un modèle figé ou de suivre des plans rigides.
La **flexibilité** est au cœur de cette pratique.

- **Exemple concret** : Lors du développement d'une application de gestion de projet, l'équipe crée un diagramme UML
  simple pour modéliser la gestion des utilisateurs. Après quelques sprints, le client demande de nouvelles
  fonctionnalités liées aux rôles d’utilisateurs, ce qui nécessite de revoir la conception initiale. L'équipe ajuste
  rapidement le modèle sans hésitation, car elle sait que les modèles doivent évoluer avec le projet.

#### Model with a Purpose (Modéliser avec un but)

Chaque modèle doit avoir un **objectif clair** et répondre à un besoin spécifique. Il n'est pas question de créer des
modèles pour remplir une documentation ou suivre une procédure, mais de résoudre un problème ou de faciliter la
compréhension d'une partie du système. Les modèles doivent toujours servir la discussion et la prise de décision.

- **Exemple concret** : Une équipe de développement doit implémenter une nouvelle API pour un site e-commerce. Plutôt
  que de créer un diagramme détaillé de l'ensemble de l'application, l'équipe crée un schéma simple illustrant les
  interactions entre le front-end et l'API, car cela suffit à clarifier les rôles des différents composants dans cette
  partie spécifique du projet.

#### Multiple Models (Utiliser plusieurs types de modèles)

Il est souvent utile d'utiliser **plusieurs types de modèles** pour représenter différentes perspectives d'un même
système. Les équipes peuvent créer des **diagrammes UML**, des **croquis** à la main, des **diagrammes de flux**, ou
même des **maquettes d'interface utilisateur**. L'essentiel est d'utiliser le modèle qui correspond le mieux à la
situation et à l'audience.

- **Exemple concret** : Lors de la refonte d’un module de gestion des stocks dans une entreprise, l’équipe utilise à la
  fois un diagramme UML pour visualiser la structure des classes, un diagramme de séquence pour illustrer le processus
  de réapprovisionnement, et une maquette rapide de l’interface utilisateur pour discuter des interactions avec le
  client.

#### Communicate Clearly (Communiquer clairement)

Les modèles doivent être facilement compréhensibles par tous les membres de l'équipe et les parties prenantes.
L'objectif n'est pas de créer des modèles complexes pour impressionner, mais d'assurer que tout le monde est sur la même
longueur d'onde. Cela implique souvent de privilégier des modèles simples et visuels plutôt que des représentations
techniques lourdes.

- **Exemple concret** : Pour expliquer l’architecture d’une nouvelle fonctionnalité à des parties prenantes non
  techniques, l’équipe de développement choisit de créer une maquette visuelle avec des annotations plutôt qu’un
  diagramme technique. Cela facilite la compréhension et encourage des retours utiles de la part des utilisateurs
  finaux.

### Les avantages d'Agile Modeling

Agile Modeling présente plusieurs avantages :

- **Simplicité et efficacité** : Les équipes se concentrent sur la création de modèles simples qui répondent aux besoins
  immédiats du projet, sans perdre de temps dans des détails inutiles.
- **Flexibilité** : Les modèles peuvent évoluer rapidement en fonction des nouvelles exigences ou des découvertes
  réalisées au fil du projet.
- **Communication** : Les modèles servent à clarifier les idées, favoriser la collaboration et éviter les malentendus.
- **Adaptabilité** : En modifiant ou en éliminant des modèles au fur et à mesure que le projet avance, l’équipe reste
  alignée sur les besoins actuels sans se laisser piéger par une documentation obsolète.

### Limites d'Agile Modeling

Bien que très utile, Agile Modeling peut présenter quelques limites :

- **Moins de formalité** : Pour les projets qui nécessitent une documentation complète et rigide (comme les projets
  réglementés), Agile Modeling peut ne pas fournir suffisamment de détails.
- **Survol des concepts** : Il y a un risque de créer des modèles trop simplifiés qui omettent des détails importants
  pour certains aspects du projet.
- **Collaboration requise** : Cette approche nécessite une collaboration étroite entre les membres de l'équipe et les
  parties prenantes, ce qui peut ne pas toujours être possible dans des environnements de travail cloisonnés.

### Utilisation de UML et Merise dans Agile Modeling

Bien que **Agile Modeling** privilégie des modèles simples et flexibles, des outils de modélisation classiques comme
**UML (Unified Modeling Language)** et **Merise** peuvent être adaptés aux pratiques agiles. Ces deux méthodologies
fournissent des cadres formels pour la modélisation des systèmes d'information, mais peuvent être utilisés de manière
allégée pour répondre aux besoins immédiats du projet.

- **UML** : UML est un langage de modélisation standard qui permet de créer des diagrammes représentant différentes vues
  d'un système, telles que des diagrammes de classes, de séquence ou d'activités. Dans Agile Modeling, UML peut être
  utilisé de manière minimaliste, en se concentrant uniquement sur les diagrammes les plus pertinents et en les
  maintenant flexibles pour permettre des ajustements au fur et à mesure du projet.

- **Merise** : Méthode de conception des systèmes d'information, Merise peut également être intégré dans une approche
  agile en se concentrant sur les **modèles conceptuels des données (MCD)** et les
  **modèles logiques des données (MLD)**, tout en évitant de trop formaliser ces modèles au départ. Cela permet de se
  concentrer sur l'essentiel et de faire évoluer les modèles en fonction des retours.

Ces outils, bien qu'issus de méthodologies plus traditionnelles, peuvent apporter une rigueur utile dans Agile Modeling,
tant qu'ils restent "juste suffisants" et adaptables aux changements.
