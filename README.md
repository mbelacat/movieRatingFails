# movieRatingFails
Semaine 23 : Reprendre un projet existantObjectif :  

Vous allez être mis dans une situation très courante de la vie d’un développeur en entreprise à savoirreprendre le travail de quelqu’un d’autre. Cette situation souvent inconfortable puisque que vous travaillez le code d’un autre est pourtant la plus courante, en effet il est rare de redévelopper un logiciel ou une application de A à Z, on reprend souvent ce qui existe déjà. Rappelez-vous que parfois ce qui existe n’est pas toujours de bonne qualité et pourtant il faudra faire avec!Il n’y a donc pas de compétences nouvelles par rapport à Symfony cette semaine mais plutôt un usage de ces compétences dans un contexte différent.  

Compétences acquises :
- Gérer ses données avec l’orm Doctrine
- Gérer ses entités avec l’orm Doctrine
- Gérer les relations de ses entités
- Créer des formulaires et gérer leur soumission- Gérer ses utilisateurs et un pare-feu
- Intégrer des bundles
- Utiliser les fixtures

Ressources et exercices :

Une seule et unique ressource est valable, la documentation officielle. Celle-ci est plutôt complète et bien expliquée:
- https://symfony.com/doc/current/index.html#gsc.tab=0


Projet à rendre

 Vous venez d’intégrer une start-up du web pour votre premier contrat de travail. Cette start-up souhaite proposer une application web afin de permettre aux internautes d’évaluer les films sortis au cinéma. L’objectif pour elle est de se rémunérer via de la publicité sur le site et aux personnes s’étant inscrites.

 Les financeurs ont été séduits par le concept et votre entreprise a levé des fonds pour engager le développement de cette application.
 Vous n’êtes pas le premier développeur qui y travaille. Jeffrey Uneconnerie avait été embauché avant vous pour mener cette application à son terme. Malheureusement les choses ne se sont pas très bien passées et ce dernier a dû être renvoyé.

 Il a produit une partie de l’application mais en l’état quasiment rien n’est fonctionnel et personne n’arrive à reprendre son code car il l’a développé seul dans son coin sans échanger avec ses collègues. Il ne travaillait pas professionnellement, à tel point qu’il n’a même pas versionné son code, vous n’avez donc aucun moyen de suivre son évolution ! La seule chose qu’il a laissé c’est undossier zip sur une clef USB suspendue à un crochet au secrétariat.

Aujourd’hui le temps presse, vous n’avez pas le temps de repartir de zéro, vous devez reprendre sonapplication, supprimer les divers bug, réagencer le code si nécessaire et poursuivre le développement en intégrant toutes les fonctionnalités qui vous semblent manquantes.

Voici le cahier des charges tel qu’il lui avait été fourni.

 L’application doit permettre de:
 - Voir tous les films du catalogue sur la page d’accueil- Voir un film avec ses caractéristiques (date, auteur, résumé...), ses évaluations et la moyenne des notes qui lui ont été attribuées
 - Pouvoir évaluer un film: une évaluation est composée d’une note de 0 à 10 et éventuellement d’uncommentaire laissé par l’utilisateur
 - Pour laisser une évaluation, l’utilisateur doit être connecté
 - L’utilisateur doit pouvoir se déconnecter- Le contenu en base de données pour les films et utilisateurs est généré via fixtures

 2)Pour aller plus loin:
 Permettre à l’utilisateur de se créer un compte- Sur la page d’un film, afficher les trois meilleures notes avec leur éventuel commentaire et les trois pires notes en les mettant visuellement en avant- Créer une page profil pour l’utilisateur où il pourra voir ses informations personnelles mais surtoutl’ensemble des évaluations qu’il a laissées et éventuellement les modifier.
 
