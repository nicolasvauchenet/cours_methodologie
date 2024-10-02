# Test Driven Development (TDD)

## Qu'est-ce que le Test Driven Development (TDD) ?

Le **Test Driven Development (TDD)**, ou développement piloté par les tests, est une méthode de développement agile qui
consiste à écrire des tests automatisés **avant** d'écrire le code de la fonctionnalité. Le processus suit un cycle
court et répétitif : les développeurs écrivent d'abord un test qui décrit le comportement attendu du code, puis ils
implémentent le code nécessaire pour passer ce test, et enfin, ils améliorent le code tout en s'assurant que les tests
continuent de passer.

Le TDD suit un cycle simple en trois étapes :

1. **Écrire un test** (Red) : Le développeur commence par écrire un test qui échouera, car la fonctionnalité n’a pas
   encore été développée.
2. **Écrire le code** (Green) : Ensuite, il écrit juste assez de code pour que le test passe.
3. **Refactoriser** (Refactor) : Une fois que le test passe, le développeur peut refactoriser le code pour l'améliorer
   tout en s’assurant que les tests continuent de passer.

## Le cycle Red-Green-Refactor

### Red - Écrire un test qui échoue

Le cycle de développement commence par l'écriture d'un **test unitaire**. Ce test est destiné à vérifier une
fonctionnalité ou un comportement spécifique. À ce stade, le code qui répond à ce test n'existe pas encore, donc le test
échoue naturellement. Cela permet de clarifier les attentes avant d'implémenter la solution.

- **Exemple** : Imaginons que nous devons développer une fonctionnalité qui calcule la somme de deux nombres. Le premier
  test pourrait être : "Lorsque j'appelle la fonction `additionner(2, 3)`, elle doit retourner 5." Ce test échouera, car
  la fonction `additionner` n'existe pas encore.

### Green - Écrire juste assez de code pour que le test passe

Après avoir fait échouer le test, le développeur écrit **juste assez de code** pour faire passer le test. À ce stade, il
n’est pas nécessaire d’écrire un code parfait ou optimisé. L’objectif est de répondre aux attentes du test de manière
minimale.

- **Exemple** : Le développeur crée la fonction `additionner(a, b)` qui retourne `a + b`. Le test passe maintenant car
  `additionner(2, 3)` renvoie bien 5.

### Refactor - Améliorer le code sans casser les tests

Une fois que le test passe, le développeur peut améliorer ou **refactoriser** le code. Cela signifie qu'il peut
optimiser la solution, la rendre plus lisible ou plus maintenable, tout en s'assurant que les tests continuent de
passer. Ce processus garantit la qualité et la robustesse du code à long terme.

- **Exemple** : Le développeur peut décider d'ajouter des vérifications dans la fonction `additionner` pour s’assurer
  que les paramètres sont bien des nombres avant de les additionner. Une fois ces modifications apportées, les tests
  doivent toujours passer.

## Avantages du TDD

### Qualité du code

Le TDD encourage les développeurs à écrire du code **plus propre** et **plus maintenable**. Le cycle Red-Green-Refactor
incite à refactoriser le code de manière régulière, ce qui évite l'accumulation de dette technique et permet de garder
le code lisible et optimisé.

### Moins de bugs

Le TDD permet de réduire les bugs en identifiant les problèmes avant même que le code ne soit écrit. En ayant des tests
unitaires couvrant chaque fonctionnalité, le TDD assure que chaque partie du code fonctionne comme prévu dès le début du
développement.

### Confiance dans les modifications

Avec des tests automatisés couvrant l'ensemble du code, les développeurs peuvent modifier ou ajouter des fonctionnalités
sans craindre de casser des parties déjà fonctionnelles. Si un changement introduit un bug, les tests existants
échoueront immédiatement, ce qui permet de le corriger rapidement.

### Documentation vivante

Les tests écrits dans le cadre du TDD servent également de **documentation vivante**. Ils montrent clairement ce que
chaque partie du code est censée faire et comment elle doit se comporter dans différents cas.

## Les défis du TDD

### Temps initial

Le TDD peut prendre plus de temps au début, car il exige d'écrire des tests avant même de commencer à coder. Cela peut
sembler un obstacle, en particulier sur des projets avec des délais serrés.

### Surspécification

Il peut arriver que des développeurs écrivent des tests qui sont trop spécifiques ou trop rigides, rendant difficile
l'ajout ou la modification de fonctionnalités plus tard. Il est donc important d'écrire des tests suffisamment flexibles
pour permettre l'évolution du code.

### Complexité des tests

Certains comportements complexes ou des interactions entre composants peuvent être difficiles à tester avec des tests
unitaires simples. Dans ces cas, des tests plus sophistiqués comme les tests d'intégration ou les tests fonctionnels
peuvent être nécessaires pour compléter le TDD.

## Outils pour le TDD

De nombreux outils existent pour faciliter l'écriture de tests et l’implémentation du TDD dans différents environnements
de développement :

- **PHPUnit** (pour les projets PHP) : Un framework populaire pour écrire des tests unitaires en PHP.
- **Jest** (pour JavaScript) : Un framework de test de Facebook, idéal pour tester des applications front-end et
  back-end.
- **JUnit** (pour Java) : Un des frameworks de test les plus utilisés dans la communauté Java.
- **RSpec** (pour Ruby) : Un outil de test orienté comportement (BDD) qui fonctionne bien avec le TDD.
- **PyTest** (pour Python) : Un framework flexible et facile à utiliser pour écrire des tests en Python.

## Exemple complet de TDD

### Scénario : Création d'une fonction de calcul de la TVA

1. **Red - Écrire le test** :
   ```php
   public function testCalculerTVA()
   {
        $this->assertEquals(20, calculerTVA(100, 20));
   }
   ```
   Ce test échoue, car la fonction calculerTVA n’existe pas encore.

2. **Green - Écrire juste assez de code** :
   ```php
   function calculerTVA($montant, $taux)
   {
        return ($montant * $taux) / 100;
   }
   ```
   Le test passe maintenant, car la fonction `calculerTVA` retourne la bonne valeur.

3. **Refactor - Améliorer le code** :  
   On peut ajouter des vérifications dans la fonction pour s’assurer que les entrées sont valides :
   ```php
   function calculerTVA($montant, $taux)
   {
        if (!is_numeric($montant) || !is_numeric($taux)) {
            throw new InvalidArgumentException('Les paramètres doivent être numériques.');
        }
        return ($montant * $taux) / 100;
   }
   ```
   Après avoir refactorisé, les tests continuent de passer, garantissant la robustesse de la solution.
