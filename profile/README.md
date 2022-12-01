# FastClap

> ## Administrative Details

### Nom du projet
Fast Clap


### Type de projet
Technique

### Description succincte du projet
Fast Clap est une solution qui permet aux assistants réalisateurs de leur faciliter la tâche de pré-production cinématographique tout en introduisant des solutions d'éco-production.

> ## Project relevancy
### What is the purpose of your project ?

La préproduction, c’est l’ensemble des démarches et actions à entreprendre en amont du tournage afin de s’assurer de son bon déroulement. Durant la préproduction, on définit et on recherche les moyens techniques, financiers, et humains qui permettront de réaliser le film. Globalement, c’est un long travail qui est fait en amont de la production.

Le travail de l’assistant réalisateur consiste à partir d’un scénario et de réaliser ce que l’on appelle un plan de travail, qui répertorie tous les décors, accessoires, costumes, personnages, acteurs, heures lieux et dates de chaque séquence Ce document de haute importance fait  réellement office de référence pour toutes les personnes travaillant sur le tournage.
C’est un travail laborieux qui rime souvent avec casse-tête et tetris pour les assistants réalisateurs.
Il n’existe aujourd’hui aucun logiciel réellement complet et qui fait office de référence pour aider ces derniers, certains même utilisent des tableaux excel faut d’alternatives.

A cela s’ajoute un réel éveil des consciences écologique dans l’industrie du cinéma et les productions doivent faire face à ce nouvel enjeu. Elles devront ainsi fournir un bilan carbone de plus en plus détaillé de leurs productions, tâche aujourd’hui extrêmement laborieuse car nouvelle et donc sans réel outils efficace.

Ainsi ces enjeux autour de la pré-production nous ont conduit à penser cette solution : une solution complète qui, partant d’un scénario, permet la définition de l’organisation du tournage tout en contrôlant son impact sur l’environnement. Toutes les informations sont centralisées pour mieux être utilisées.


### List your competitors
Filmustage - Dépouillement automatique d'un scénario (exclusivement en anglais)
Movie Magic Scheduling - Outil permettant de générer un plan de travail au format américain
Outlook Movie - Outil de communication et planning pour des tournages
EcoProd (Carbon Clap) - Outil permettant de calculer le bilan carbone d’une tournage à l’issu de celui-ci
Par rapport à la concurrence notre projet se démarquera par:
Une solution qui accompagne l'édition du scénario jusqu'au plan de travail français. Ainsi plus besoin pour les assistant réalisateurs de naviguer entre différents logiciels lors de la phase de pré-production, ou d’utiliser des outils non optimisés.
Un espace dédié aux productions pour avoir un contrôle constant sur leur impact carbone.

> ## Customers segmentation

### Define your project segmentation *
Notre projet est essentiellement orienté pour les assistants réalisateurs mais aussi les boites de productions françaises en général.
Pour les assistants réalisateurs: dans le cadre de la pré-production cinématographique. Et notamment les étapes clés du dépouillement et de la réalisation d’un plan de travail dynamique et modulable.
Pour les boîtes de productions françaises: dans le cadre de la pré-production, avec un espace pour contrôler leur impact carbone et permettre d’extraire toutes les informations demandées par les différents acteurs de l’industrie du cinéma (ex: CNC).  Notre produit s’adapte aussi bien aux boîtes de production de cinéma court et long métrage qu’au production de séries ainsi qu’à celles de publicités.

> ## Functional scope of the project

### Define your short term goals

Les objectifs à court terme (SEMESTRE 5) sont:
Proposer les bases de notre application web et de son API.
Permettre à un utilisateur de :
Se connecter ou créer un compte pour commencer un nouveau travail.
Importer un scénario
Dépouiller facilement en proposant un système de tag directement sur le document.
Renseigner des informations supplémentaires non présentes sur le scénario (lieu exact, adresse des acteurs, disponibilités etc …).
Visualiser son dépouillement par catégories (acteurs, personnages, lieu, décor etc …).

### Define your long term vision (this part should be the most important and detailed of this form)

Les objectifs sur le long terme, c’est à dire après la forward jusqu'au déploiement final du projet sont:
Mise en place d’une CI/CD et d’un workflow de développement propre.
Mise en place et déploiement de l’application web de son serveur et de sa base de données.
A partir du travail réalisé pendant la forward et des informations ainsi récupérées, permettre à un utilisateur de générer automatiquement un premier plan de travail.
Permettre de modifier facilement ce plan de travail et d’accéder à chaque information facilement.
Fournir toute une partie réservée à la production qui leur permettra de rentrer leur budget pour chaque catégorie.
Pouvoir à partir des informations du plan de travail et des informations sur le budget fournies par la production établir un bilan carbone sous la forme d’un Eco Dashboard.
Pouvoir interagir avec cet Eco Dashboard et avoir en temps réel des anticipations et prévisions intelligentes. La production pourra alors à chaque instant connaître l’impact carbone d’une décision et se verra proposer des solutions ou suggestions pour réduire cet impact.
Développement d’une application mobile plus simple permettant à toute l’équipe d’être informée de l’actualité du tournage, de recevoir des notifications ou encore de réagir à certains événements.
Afin d'avoir une certaine consistance sur le long terme, voici le calendrier des features et divers déploiements prévus pour notre application :

#### Semestre 6 - (Mars 2023 - Août 2023)
CI/CD & workflow :
Mise en place de toute l’architecture globale du projet. C’est a dire:
Serveur de développement et de production
Workflow de développement et Quality Assurance
Connexion entre les différents services
Toute cette partie est clé dans la réalisation du projet puisqu’elle nous permettra de développer sereinement et d’avancer sur les features dans un environnement stable et performant.

Plan de travail :
Mise en place d’un plan de travail modulable. Celui-ci sera basé sur les données collectées lors de l’upload du scénario et de la phase de saisie des informations clés.
Une fois les données préliminaires collectées à partir du scénario, l’assistant réalisateur aura la possibilité de préciser les acteurs où lieux de tournages à l'aide de fiches à remplir.
Une fois celles-ci disponibles, il nous restera alors qu’à les agencer et dans un tableau dynamique qui pourra être ajusté par l'utilisateur selon ses contraintes. Dans un second temps lors de sa manipulation, il permettra de voir les économies énergétiques calculées selon la réduction des trajets et l’utilisation des ressources.

#### Semestre 7 - (Septembre 2023 - Février 2024)
Eco-dashboard :
Pour permettre aux producteurs d’avoir un aperçu global d’une prévision de la consommation carbone de la production du film.
Pour réaliser cela, une partie de l’équipe créera un programme qui récupérera les données du plan de travail, acteurs, lieux et qui grâce à ces données fera un différents calculs sur la consommation carbone de la production du film. Les résultats de ces calculs seront affichés sur forme de graphes.

Budget dashboard :
Un autre partie de l’équipe s’occupera de réaliser un programme qui calcule, en fonction des différentes données récupérées du plan de travail, acteurs, lieux et d’autres données complétés par le producteur, le coût de production du film.



Mise en place d’un site vitrine :
Une dernière partie de l’équipe s’occupera de réaliser un site vitrine pour permettre une meilleure visibilité de notre projet.

#### Semestre 8 - (Mars 204 - Août 2024)
Gestion des feuilles scriptes/services :
Mise en place d’un système de génération et modification et partage de fiches scriptes et services.
Elle permet à la fois d’écrire un rapport pour le monteur en « cerclant » les bonnes prises et en précisant à chaque prise, les commentaires du réalisateur pour que le monteur sache quelle prise regarder. Elle doit également s’assurer en permanence que la continuité du film est respectée (jeux d'acteur, accessoires présents, faux raccords,…)
La fiche de service résume toutes les informations importantes de la journée du lendemain comme le lieu de tournage, les horaires,… cela permet à chacun d’avoir toutes les informations nécessaires.
partie production
Demander à Victor

#### Semestre 9 - (Septembre 2024 - Février 2025)
En réflexion


> ## Resources

### Human resources and organization

Clement FERNANDES:  Développeur Frontend Web et Mobile - Responsable UX/UI.
Gurvan LE LETTY:  Développeur Backend - DevOps.
Martin VANAUD: Développeur Backend - DevOps.
Maxime CARABINA: Développeur Frontend Web.
Tibo PENDINO: Développeur Backend - Responsable Qualité.
Valentin DURIEUX:  Développeur Frontend Web et Mobile.
Victor PALLE: Développeur Fullstack - Responsable relations avec professionnels et marketing.


### Technical resources

API : Développée en NestJS (TypeScript) pour des raisons de simplicité et de sécurité. Beaucoup de modules sont fournis nativement dans ce framework JavaScript.
Application Web: Le frontend de la web-app sera développé en ReactTS (framework ReactJS avec du TypeScript). Ce sont des technologies répandues, faciles à prendre en main, avec une communauté conséquente et ainsi facile à entretenir.
Application Mobile: Flutter pour les fonctionnalités de cross-plateforme (téléphones Android et iOS) et la simplicité du langage.


Serveur de déploiement en développement et production pour un workflow et une CI/CD propre

### Partnerships

AdVitam Court - Société de production cinématographique spécialisée dans les courts-métrages. Ils nous offrent la possibilité d’assister à des tournages, voir comment leurs métiers fonctionnent pour répondre efficacement à leurs besoins. Puis dans un second temps nous pourrons en profiter pour leur faire tester notre outil sur le terrain afin d’avoir des retours sur son utilisation.
CNC - Le Centre National du Cinéma sera un allié de taille puisque c’est l’acteur majeur en France dans le secteur de l’audiovisuel. Notamment sur la partie éco-responsabilité nous pourrons nous servir de leurs documents types
Ademe -  Elle participe à la mise en œuvre des politiques publiques dans les domaines de l’environnement, de l’énergie et du développement durable, par la mise à disposition de ses données afin de permettre à différents acteurs économiques de progresser dans leur démarche environnementale et de démultiplier les actions en faveur de la Transition écologique.

> ## Project context

### Existing constraints and how to handle them
Contrainte(s) légale(s):
Contrainte(s) technique(s):
Contrainte(s) économique(s):

### Legal framework
[En réflexion]
