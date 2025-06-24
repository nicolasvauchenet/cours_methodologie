## Présentation des méthodes traditionnelles

### Introduction aux méthodes traditionnelles

Les méthodes traditionnelles de gestion de projet sont des approches séquentielles et prédictives, dans lesquelles
chaque étape du projet doit être complétée avant de passer à la suivante. Ces méthodes sont particulièrement adaptées
aux environnements où les exigences sont clairement définies dès le départ et peu susceptibles de changer. Elles ont été
utilisées avec succès dans des industries telles que la construction, l’aéronautique ou encore l’ingénierie. Les deux
méthodes traditionnelles les plus connues sont le **cycle en V** et le **modèle Waterfall**.

### Le modèle Waterfall

#### Définition

Le modèle Waterfall, ou modèle en cascade, est l’une des approches les plus anciennes en gestion de projet. Il s'agit d'
un modèle linéaire où chaque phase de développement est réalisée entièrement avant que la suivante ne commence. Les
principales phases du modèle Waterfall sont :

- **Recueil des exigences** : Toutes les exigences sont documentées en amont.
- **Conception** : Une architecture détaillée est définie pour le projet.
- **Développement** : Les développeurs construisent le produit en suivant les spécifications.
- **Tests** : Les tests sont effectués pour vérifier que le produit respecte les exigences.
- **Déploiement** : Le produit est livré au client.
- **Maintenance** : Le produit est mis à jour et corrigé après sa livraison.

#### Exemple concret

Prenons l'exemple de la construction d'un pont. Dans ce type de projet, toutes les spécifications sont connues à
l'avance : les dimensions du pont, les matériaux à utiliser, les réglementations à respecter. Chaque phase de
construction (planification, fondations, élévation de la structure, etc.) suit l'autre de manière rigide. Une fois que
les fondations sont coulées, il n'est plus possible de revenir en arrière pour les modifier. Cela illustre bien l’idée
du modèle Waterfall : un processus linéaire où il est difficile et coûteux de revenir en arrière pour apporter des
modifications.

### Le cycle en V

#### Définition

Le **cycle en V** est une méthode similaire au modèle Waterfall, mais elle met davantage l'accent sur les phases de
validation et de vérification. Chaque phase de développement a une phase de validation correspondante, créant ainsi une
structure en forme de "V". Voici les principales étapes :

- **Phase de spécification** : Rédaction des exigences du projet.
- **Conception fonctionnelle** : Définition des fonctionnalités du produit.
- **Conception technique** : Élaboration de l’architecture technique.
- **Implémentation** : Développement du produit.
- **Tests unitaires** : Validation du code à un niveau bas.
- **Tests d’intégration** : Vérification des interactions entre les différents composants.
- **Tests de validation** : Vérification que le produit final répond aux exigences.
- **Tests d’acceptation** : Le produit est testé par le client avant sa mise en production.

#### Exemple concret

Un bon exemple d’application du cycle en V se trouve dans l’industrie aéronautique. Prenons le développement d’un
nouveau modèle d’avion. Ce processus commence par des spécifications très détaillées : capacité de passagers, autonomie,
vitesse de croisière, etc. Chaque phase de conception (fonctionnelle, puis technique) est suivie par des phases de tests
approfondis (tests en soufflerie, tests structurels, simulations de vol). Chaque élément de l'avion (ailes, moteurs,
systèmes électroniques) est testé séparément, puis intégré au fur et à mesure que les tests avancent. Enfin, l’avion est
validé dans des conditions réelles avant sa livraison à la compagnie aérienne. Le cycle en V permet ici de garantir une
traçabilité stricte et une validation continue à chaque étape critique du projet.

### Limites des méthodes traditionnelles

Bien que ces méthodes soient très efficaces pour des projets où les exigences sont clairement définies et stables, elles
présentent plusieurs inconvénients dans des environnements dynamiques et incertains, notamment :

- **Rigidité** : Une fois qu’une phase est terminée, il est difficile de revenir en arrière sans coûts importants.
- **Temps de retour tardif** : Dans des projets complexes comme le développement logiciel, le produit n'est souvent
  testé qu’à la fin du cycle, ce qui peut révéler des erreurs tardivement.
- **Manque de flexibilité** : Si les exigences changent en cours de projet, il peut être difficile d'intégrer ces
  changements.

#### Exemple concret des limites

Dans le développement d'un logiciel bancaire avec le modèle Waterfall, toutes les exigences sont définies en début de
projet. Cependant, au moment où le développement est presque terminé, la réglementation bancaire évolue, imposant de
nouvelles règles de sécurité. Avec le modèle Waterfall, intégrer ces nouvelles exigences nécessiterait de revenir à la
phase de conception, ce qui impliquerait de refaire tout le processus de développement et de test, entraînant des délais
et des coûts supplémentaires. Cette rigidité rend les méthodes traditionnelles inadaptées dans des contextes où les
changements sont fréquents.

### Quand utiliser les méthodes traditionnelles ?

Malgré leurs limites, les méthodes traditionnelles restent pertinentes dans certains contextes spécifiques :

- **Projets avec des exigences stables** : Lorsque les besoins du projet ne sont pas susceptibles de changer, par
  exemple dans la construction d’infrastructures (ponts, routes, bâtiments).
- **Projets réglementés** : Les industries comme l’aéronautique, l’automobile ou le domaine médical, où des normes
  strictes doivent être respectées, bénéficient des méthodes traditionnelles en raison de la traçabilité qu’elles
  offrent.
- **Projets à risques élevés** : Les projets où les erreurs coûtent cher (par exemple, la conception de systèmes de
  sécurité critiques) tirent parti de l'approche de validation du cycle en V pour minimiser les risques.

#### Exemple concret d’utilisation adaptée

Dans le domaine de la construction de gratte-ciels, toutes les étapes de la construction sont planifiées en amont, y
compris la conception des fondations, la structure, et même les plans d’évacuation d’urgence. Le processus de validation
est rigoureusement encadré par des normes de sécurité. Les méthodes traditionnelles sont donc adaptées ici, car tout
changement en cours de construction pourrait affecter la stabilité de la structure et impliquer des coûts très élevés.

### Comparaison entre Waterfall et le cycle en V

Bien que les deux méthodes soient basées sur une approche séquentielle, quelques différences les distinguent :

- **Approche de validation** : Le cycle en V met davantage l'accent sur la validation et les tests tout au long du
  processus, tandis que Waterfall attend la fin du développement pour tester l’ensemble du produit.
- **Retour en arrière** : Le cycle en V permet un retour en arrière plus systématique lors des phases de test, ce qui
  n’est pas possible dans Waterfall.
- **Adaptation** : Waterfall est principalement utilisé dans des contextes où le produit final doit être livré en une
  seule fois, alors que le cycle en V est mieux adapté aux projets où chaque composant du système est critique (par
  exemple, les systèmes embarqués).

### Évolution vers des méthodes hybrides

Face aux critiques de rigidité et de manque de flexibilité, de nombreuses entreprises ont commencé à explorer des
méthodologies **hybrides** dans les années 2000, en combinant des éléments des approches traditionnelles et agiles. Cela
a donné naissance à des méthodologies comme le **Waterfall agile** (où les phases de Waterfall sont entrecoupées de
cycles agiles) ou le **cycle en V adaptatif**.

#### Exemple concret de méthode hybride

Dans le développement d’un système de gestion pour un hôpital, une entreprise a adopté un **modèle hybride** : les
phases de spécification et de conception technique ont été réalisées avec le cycle en V pour garantir la traçabilité des
exigences réglementaires, mais le développement s’est fait de manière itérative (inspirée de Scrum) afin de permettre
des ajustements fréquents sur les fonctionnalités en fonction des retours des utilisateurs finaux. Cette combinaison a
permis de réduire les délais de livraison tout en respectant les normes strictes du domaine médical.

## Exercice pratique

### [Cycle en V ou Waterfall ?](../Exercices/%C3%89nonc%C3%A9/02%20-%20Pr%C3%A9sentation%20des%20m%C3%A9thodes%20traditionnelles%20-%20Exercice.md)
