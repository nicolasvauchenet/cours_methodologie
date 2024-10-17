# Projet d'évaluation UML - Document Apprenant

## Objectif :

L'objectif de cette évaluation est de concevoir un système informatique pour un festival de musique, en utilisant les
principes de modélisation UML. Vous devrez modéliser les interactions, les processus, et la structure des données
nécessaires pour la gestion efficace du festival.

## Contexte :

Le festival de musique **[VOTRE NOM ICI]** se déroule sur trois jours avec deux scènes distinctes : une grande scène
pour les têtes d'affiches internationales et une petite scène pour des groupes émergents ou locaux. Le système
informatique doit permettre la gestion complète du festival, allant de la programmation des artistes, à la logistique du
matériel, en passant par la billetterie et la communication avec les festivaliers.

Le festival compte environ **30 artistes** dirigés par un **régisseur artistique**, **500 bénévoles** dirigés par des
**régisseurs techniques et logistiques**, et un flux de **15 000 visiteurs** par jour. Vous êtes chargés de concevoir
une solution informatique qui assurera la fluidité des opérations pendant le festival.

## Exigences fonctionnelles à modéliser :

- **Programmation et horaires des artistes :** Gestion des créneaux horaires sur les deux scènes.
- **Accueil et services aux artistes :** Coordination de l'accueil, de l'hébergement, et des services de catering.
- **Logistique du festival :** Organisation du matériel nécessaire, coordination des équipes de techniciens, de
  sécurité, et des bénévoles.
- **Communication et publicité :** Gestion des campagnes publicitaires et communication avec le public.
- **Gestion de la billetterie et services sur site :** Vente de billets et gestion des services aux visiteurs.
- **Gestion des budgets et des ressources :** Suivi des dépenses, des recettes, et des ressources humaines.
- **Sécurité et gestion des urgences :** Planification des mesures de sécurité et gestion des situations d'urgence.
- **Gestion des partenariats et sponsors :** Coordination des partenariats avec les marques et sponsors du festival.
- **Analyse des performances et retours d'expérience :** Collecte des données sur les performances et les retours des
  festivaliers.

## Détail des processus critiques :

Voici des explications supplémentaires sur certains processus cités dans les exigences fonctionnelles. Ces précisions
doivent guider vos choix dans la modélisation UML.

- **Programmation des artistes :** Il s'agit de gérer les créneaux horaires des artistes sur les deux scènes (grande
  scène et petite scène). Chaque artiste doit avoir un créneau attribué, sans conflit d'horaire, et la logistique (
  sonorisation, éclairage) doit être prête pour chaque performance.
- **Accueil des artistes :** Ce processus couvre la coordination de l'hébergement, du transport, et des services de
  restauration pour les artistes. Il inclut également l'accompagnement des artistes à leur lieu de performance et la
  gestion des demandes particulières (ex. : loges spécifiques, services de sécurité).
- **Logistique :** La logistique du festival concerne l'organisation du matériel nécessaire pour chaque scène (
  instruments, équipements sonores, etc.), la coordination des équipes techniques (techniciens son, éclairage), la
  sécurité (vigiles, agents de sécurité), et la gestion des bénévoles pour différentes tâches.
- **Communication et publicité :** Ce processus inclut la gestion des campagnes publicitaires, la promotion des artistes
  et des événements, et la communication avec les festivaliers par divers canaux (réseaux sociaux, newsletters,
  affiches, etc.).
- **Gestion de la billetterie et des services sur site :** Ce processus concerne la vente de billets (en ligne et sur
  place), la gestion des points d'accès (entrée/sortie), ainsi que les services offerts aux festivaliers sur place (
  restauration, stands de produits dérivés).
- **Gestion des budgets et des ressources :** Ce processus couvre le suivi des dépenses (ex. : cachets des artistes,
  location de matériel), des recettes (ex. : vente de billets, merchandising), ainsi que la gestion des ressources
  humaines (ex. : allocation des bénévoles, techniciens et personnel administratif). Le système doit permettre de
  surveiller les coûts et les revenus en temps réel, tout en veillant à optimiser l'utilisation des ressources.
- **Sécurité et gestion des urgences :** Il est crucial d'assurer la sécurité des festivaliers et des artistes. Ce
  processus inclut la planification des mesures de sécurité (ex. : déploiement des agents de sécurité, gestion des
  accès, surveillance des zones critiques) ainsi que la préparation aux situations d'urgence (ex. : évacuations,
  incidents techniques, premiers secours). Le système doit permettre une coordination rapide entre les équipes sur le
  terrain en cas de crise.
- **Gestion des partenariats et sponsors :** Le festival compte sur des partenaires et sponsors pour financer et
  promouvoir l'événement. Ce processus inclut la coordination avec les marques sponsors (ex. : mise en place de stands,
  affichage des logos, participation aux activités), ainsi que la gestion des contrats et accords de partenariat. Le
  système doit permettre un suivi des engagements contractuels, des contreparties offertes aux sponsors, et de la
  visibilité accordée à chaque partenaire.
- **Analyse des performances et retours d'expérience :** Une fois le festival terminé, il est important de collecter et
  d'analyser les données sur les performances des artistes (ex. : qualité des performances, retours du public) et
  l'organisation globale (ex. : satisfaction des festivaliers, incidents signalés). Ce processus permet de tirer des
  leçons pour améliorer les futures éditions du festival. Le système doit inclure des fonctionnalités de collecte
  d’avis, d’analyse des retours (quantitatifs et qualitatifs), et de reporting.

## Étapes de l'évaluation :

1. Introduction et présentation du contexte (30 minutes)

    - Présentation du festival de musique et de l'infrastructure actuelle.
    - Discussion des exigences fonctionnelles du système informatique à concevoir.

2. Analyse du contexte et des exigences (1 heure)

    - Comprendre les besoins du festival et la structure des événements.
    - Analysez et regroupez les exigences fonctionnelles en catégories : programmation des artistes, accueil,
      logistique, communication, billetterie.

3. Modélisation UML (4 heures)

    - **Diagramme de cas d'utilisation** (30 minutes) : Identifiez les acteurs (artistes, bénévoles, festivaliers,
      responsables de la billetterie, techniciens) et leurs interactions avec le système.
    - **Diagramme d'activité** (30 minutes) : Choisissez deux processus critiques parmi la billetterie, la
      programmation, l'accueil des artistes, ou la gestion des urgences, et détaillez-les.
    - **Diagramme de séquence** (45 minutes) : Décrivez une interaction clé entre un acteur et le système, comme la
      vente de billets ou l'accueil des artistes.
    - **Diagramme de classes** (1h30) : Modélisez la structure du système avec les différentes classes : artistes,
      visiteurs, billets, scènes, créneaux horaires.
    - **Modèle entité-relation** (45 minutes) : Créez une base de données relationnelle qui permettra de stocker les
      informations sur les artistes, les billets, les événements, etc.

4. Rapport de présentation des livrables (1 heure)

    - Rédigez un rapport structuré avec une explication de vos choix pour chaque diagramme et une conclusion sur la
      modélisation globale du système.

5. Présentation et restitution (20 minutes par groupe)

    - Présentez vos diagrammes, justifiez vos choix et répondez aux questions.

## Modèle de rapport final :

Voici un modèle pour guider la rédaction du rapport final. Ce modèle aidera les apprenants à structurer leur livrable de
manière claire et professionnelle.

1. Résumé du projet :

    - Présentation du contexte du projet (festival de musique).
    - Objectifs du système informatique à concevoir.
    - Rappel des exigences fonctionnelles majeures.

2. Diagrammes UML :

    - Diagramme de cas d'utilisation : Présentez les acteurs et expliquez leurs rôles dans le système.
    - Diagramme d'activité : Détaillez les processus critiques choisis, justifiez les choix de modélisation.
    - Diagramme de séquence : Montrez comment les différentes entités interagissent lors de la réalisation des processus
      critiques.
    - Diagramme de classes : Décrivez la structure du système, les classes principales, et justifiez les relations entre
      elles.
    - Modèle entité-relation : Expliquez comment vous avez structuré les données et comment elles sont liées.

3. Conclusion :

    - Résumez les points forts du système modélisé.
    - Expliquez les choix de conception (simplifications ou ajustements par rapport aux contraintes).
    - Mentionnez les défis rencontrés lors de la modélisation.

## Critères d'évaluation :

- Pertinence et complétude des diagrammes UML produits.
- Cohérence et précision des modélisations par rapport aux exigences fonctionnelles.
- Clarté de la présentation et de la documentation produite.
- Capacité à justifier les choix de conception lors de la présentation orale.

## Remarques :

- Vous pouvez utiliser l'outil de votre choix pour la modélisation UML (Draw.io, Lucidcharts, plantUML) et la rédaction
  du rapport de présentation (à livrer en PDF).
- Vous pouvez utiliser des ressources externes pour vous aider dans votre travail, mais vous devez citer vos sources.
- Vous devez travailler en équipe tout au long de l'évaluation.
- Vous devez remettre votre rapport et vos diagrammes à la fin de l'évaluation.

Bonne chance ! N'hésitez pas à poser des questions si vous en avez.
