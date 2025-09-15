
#### Initiation au versioning
Pourquoi utiliser un outil de versioning lors d’un projet ?

Dans le développement d’un projet informatique, un outil de versioning est indispensable. Il permet de garder une trace de toutes les modifications, de travailler à plusieurs de manière organisée, et de maintenir une version stable du code.

### Qu’est-ce que le versioning ?
Le versioning consiste à enregistrer chaque changement apporté à un ou plusieurs fichiers. C’est un élément clé dans la gestion de projets, surtout en développement logiciel ou en design numérique. Grâce à lui, les équipes peuvent :

revenir à une version précédente en cas d’erreur ou de changement de choix,
collaborer efficacement en travaillant chacun sur des parties différentes du projet,
éviter la perte ou l’écrasement de données importantes.

### À quoi sert de "versioner" son code ?
Versionner son code présente plusieurs avantages :

Suivi clair de l’évolution du projet : chaque modification peut être accompagnée d’un message explicatif, ce qui facilite la compréhension du chemin parcouru.
Travail en parallèle : plusieurs développeurs peuvent avancer sur leurs propres fonctionnalités ou correctifs sans perturber la version principale du projet.
Sécurité et stabilité : si une nouvelle modification casse quelque chose ou n’est pas satisfaisante, il est toujours possible de revenir en arrière.
En résumé, le versioning n’est pas seulement un historique : c’est aussi un outil de collaboration et de fiabilité pour assurer la qualité et la continuité d’un projet.



Les types de versioning
Il existe principalement deux grands modèles de systèmes de gestion de versions :

a) Les systèmes centralisés (Centralized Version Control Systems – CVCS)
Tout le code et son historique sont stockés sur un serveur central.
Les développeurs doivent se connecter à ce serveur pour récupérer la dernière version ou déposer leurs changements.
Exemple : SVN (Subversion), CVS, Perforce.
Avantages :

Simplicité de mise en place.
Une seule “source de vérité”.
Limites :

Dépendance forte au serveur central (si le serveur tombe, plus personne ne peut travailler).
Pas de travail hors-ligne complet (l’historique est sur le serveur).

b) Les systèmes distribués (Distributed Version Control Systems – DVCS)
Chaque développeur possède une copie complète du projet, y compris tout l’historique.
Le travail peut se faire hors-ligne, puis être synchronisé avec les autres.
Exemple : Git, Mercurial, Bazaar.
Avantages :

Travail hors-ligne possible.
Pas de dépendance unique à un serveur (chaque copie est un dépôt complet).
Collaboration plus flexible grâce aux branches.
Limites :

Courbe d’apprentissage plus élevée.
Gestion parfois complexe pour les débutants.
🔹 2. Les principaux outils de versionning
Quelques outils connus :

CVS : un des premiers systèmes centralisés, aujourd’hui obsolète.
SVN (Subversion) : système centralisé encore utilisé dans certaines entreprises.
Mercurial : concurrent direct de Git, distribué, mais moins populaire.
Bazaar : autre DVCS, peu utilisé aujourd’hui.
Git : le plus répandu, système distribué, utilisé partout.
Plateformes collaboratives basées sur Git :
GitHub
GitLab
Bitbucket


🔹Présentation de Git
Git est un système de gestion de versions distribué créé en 2005 par Linus Torvalds (le créateur de Linux).

Principes fondamentaux :
Chaque développeur possède une copie complète du projet (y compris tout l’historique).
Les modifications sont enregistrées dans des commits, qui décrivent l’évolution du code.
Les développeurs peuvent créer des branches pour expérimenter ou développer de nouvelles fonctionnalités sans toucher à la version principale.
Les branches peuvent être fusionnées (merge) une fois validées.
Git permet de revenir facilement à un état antérieur du projet.


Pourquoi Git est devenu le standard ?
Rapide et efficace même sur de grands projets.
Travail hors-ligne possible.
Flexibilité avec branches et workflows adaptés (Git Flow, trunk-based, etc.).
Large adoption mondiale → énormément de documentation, d’outils et de plateformes (GitHub, GitLab, etc.).


🔹Installation de Git

Commandes:
### git init :
La commande git init initialise un nouveau dépôt Git dans un répertoire, le transformant ainsi en un espace de travail versionné. Elle crée un sous-dossier caché .git qui contient toutes les métadonnées, l'historique et les configurations nécessaires au suivi des modifications et à l'utilisation des autres commandes Git. C'est généralement la première commande exécutée pour un nouveau projet.

### les branches (branch)
Dans Git, une branche (ou "branch" en anglais) est une ligne de développement indépendante et parallèle qui permet d'isoler des modifications ou des nouvelles fonctionnalités du code principal sans perturber le projet en cours. Elle fonctionne comme un pointeur léger vers un commit spécifique, et ce pointeur se déplace automatiquement vers le dernier commit effectué sur cette branche. Les branches sont fondamentales pour le travail collaboratif, car elles permettent à plusieurs développeurs de travailler sur différentes tâches simultanément sans interférer les uns avec les autres.

### git branch

### les commits
Un commit est l'action d'enregistrer une transaction ou une série de modifications, comme un « instantané » d'un projet, dans un système de contrôle de version ou une base de données. Dans des outils comme Git, un commit capture l'état d'un projet à un moment précis, accompagné d'un message expliquant les changements, et permet de revenir à une version antérieure ou de restaurer des modifications.

### git add .
La commande git add est utilisée dans Git pour placer les modifications d'un ou plusieurs fichiers dans la zone de préparation (aussi appelée staging area), avant de les enregistrer de manière permanente dans l'historique du projet avec git commit. Elle permet de sélectionner précisément les changements que vous souhaitez inclure dans votre prochain commit, offrant ainsi un contrôle fin sur l'historique de votre version de code. 

### git commit -m "message du commit"

### git branch "nom_de_la_branche"
### git switch "nom_de_la_branche de switch"

###################~ Github ~################

## def github

## Comment créer un dépôt github

## comment lier un dépôt github à un projet en local

## C'est quoi le pull request
