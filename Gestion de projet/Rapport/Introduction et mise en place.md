La gestion de projet est un élément crucial pour que le projet se déroule sans accro, surtout lorsque l'on est sur une méthodologie agile car il faut que les processus soient clairs pour que tout le monde comprenne quoi faire et comment le faire.
## Organisation
### Ressources humaines
Pour ce qui est de l'organisation, nous avons commencé le projet par prévoir les différentes équipes dont nous aurions besoin et d'y affecter des personnes par préférence.

Cependant, étant tous des ingénieurs des médias avec des capacités relativement similaires, ces équipes sont une base et non une structure fixe. Tout le monde peut aider ou avoir envie de faire autre chose à un moment ou à un autre. L'utilité de ces affectations est de toujours avoir des personnes de contact si un membre de l'équipe d'un autre secteur a une interrogation sur un domaine sur lequel il n'a pas collaboré.

![[repartitionEquipes.jpg]]
### Temporelle
Le projet dure 4 semaines, nous avons dû adapter la réalisation du projet à ce délai. De plus, les deux premiers sprint durent 4 jours étant donné que le projet a dû commencer avec une demi-journée de retard à cause de l'organisation des groupes et du vendredi 29 mars qui est férié.

Nous avons décidé de répartir les étapes importantes du projet sur les sprints afin d'avoir une base sûre :
1. Le premier sprint est à la fois le premier et le sprint zero. Son but est d'organiser l'équipe et de mettre en place les différents outils dont nous aurons besoin pour communiquer et pour collaborer. En parallèle l'équipe se chargera du pré-projet qui contient l'étude de marché, le benchmark, le branding et l'initiation des stratégies marketing B2C et B2B.
2. Le deuxième sprint sera consacré à établir les bases du produit avec les informations que l'on aura recueillies durant le premier sprint. Ce sera donc principalement des travaux concernant l'UI/UX, l'architecture et l'infrastructure de développement ainsi que l'établissement final de la stratégie marketing.
3. Le troisième sprint sera constitué d'une phase de réalisation qui concernera toutes les productions multimédia, allant des visuels au produit final. Cela nous permettra d'avoir rapidement le gros du projet afin de le présenter au PO et au noyau pédagogique.
4. Le dernier sprint sera un sprint de finalisation et d'user testing si l'on a le temps. Il nous permettra de finaliser le produit afin de le rendre présentable. Une partie de l'équipe sera, durant cette phase, sur la transcription du rapport en markdown vers un modèle final mis en page ainsi que sur la présentation.

Beaucoup de ces tâches, comme la production UI/UX, se font de manière itérative tout au long du projet. Elles se réaliseront en effet de la sorte, mais ces jalons sont prévus pour avoir une bonne direction et ainsi permettre à d'autres tâches de débuter sans être bloquées car elles sont dépendantes d'autres.

![[organisationHebdomadaire.jpg]]
## Mise en place de la gestion de projet agile
### Sprint planning
Le Sprint Planning est le première étape, elle se fait en début de Sprint afin de l'initier. Pour se faire il faut respecter plusieurs étapes.

Tout d'abord le Product Owner doit trier le backlog contenant les User Stories par priorité afin de faire connaître au Scrum Master les tâches à réaliser et leur pertinence. Cela permet de mieux s'organiser pour avoir un livrable correspondant aux attentes et aux impératives du client en fin de Sprint.

Ensuite, le Scrum Master réalise les issues (tâches) à faire et passe vers les équipes travaillant sur le projet pour savoir où elles en sont. Cela permet d'analyser la situation et de gérer les cas de tâches bloquantes ou d'atomiser et de répartir les tâches si elles prennent plus de temps que prévu. En fonction de la vélocité de l'équipe et des tâches en cours, le Scrum Master doit ensuite passer les tâches de "backlog" à "to-do" pour pouvoir garantir une charge constante et réalisable sur l'équipe.

Pour finir, le Product Owner réorganise la priorité des tâches en fonction des modifications afin de déterminer les tâches importantes à faire si l'équipe a un gain en vélocité.
### Tableau Kanban
Pour ce qui est du tableau Kanban, nous avons choisi d'utiliser [Github Project](https://docs.github.com/fr/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) car il permet d'affecter des issues aux tâches et d'avoir constamment un lien sur les branches Git. Cette solution semble être particulièrement optimale en ce qui concerne le développement, mais nous avons pris la décision d'y intégrer aussi la documentation, soit toutes les tâches, afin d'avoir un seul tableau Kanban pour le projet dans son entièreté.

Pour alléger la tâche des personnes rédigeant le rapport, il est bien plus simple d'avoir un format de texte brut à copier/coller. C'est pour cela que nous avons choisi de faire le rapport en markdown sur [Obsidian](https://obsidian.md/). Cela nous permet aussi d'intégrer le rapport et de le review simplement dans Github au lieu de passer par des éditeurs de texte classiques qui peuvent complexifier le travail. Cela nous permet d'avoir un workflow simple et fluide.

Pour ce qui est des reviews, nous avons bloqué le push sur la branche main de Github ce qui oblige les équipes à faire des issues pour chaque tâche. Cette méthodologie oblige une autre personne à review le travail de la première, ce qui nous permet d'avoir constamment un regard critique et nouveau sur le travail et nous permet de remonter les erreurs et problèmes.

Cela permet aussi aux membres de l'équipe de review des tâches à des moments où ces derniers sont moins productifs, afin de toujours avoir quelque chose de différent à faire et de pouvoir changer de tâche afin de ne pas fixer un écran blanc d'un regard vide.
![[kanban.png]]
### Dailies
Les dailies ont lieu tous les jours à 10h du matin et doivent durer entre 30 et 40 minutes maximum. Leur but n'est pas de constater le travail effectué en faisant la "police" mais d'annoncer des blocages et de trouver des solutions ou de partager des visions différentes sur ce qui a été fait.

Toute demande qui n'a pas été prévue dans le projet, que ce soit de l'ordre de la collaboration ou de la demande de matériel, doit être faite à ce moment là de préférence.
Des PV sont établis sur tous les dailies afin de pouvoir retracer les changements et les spécifications demandées ou annoncées.
### Sprint rétrospectives
Les rétrospectives sont la dernière étape d'un sprint. Pour que tout se passe bien, nous avons établi un processus clair.

Premièrement, les personnes annoncent le travail effectué et en font de préférence des démonstrations afin de pouvoir peut-être soulever des questions.

Ensuite, nous utilisons [RetroTool](https://retrotool.io/) qui est un outil en ligne, permettant d'émettre trois types de réactions différentes:
1. Les "start" sont des idées qui pourraient résoudre, débloquer ou améliorer le processus de travail global
2. Les "stop" sont des choses qu'il faut impérativement arrêter de faire afin d'optimiser la productivité sur le projet
3. Les "continue" sont des idées qui ont été apportée en cours de projet et qui seraient intéressantes à intégrer afin d'améliorer la productivité sur le projet

![[retrotool.png]]

Pour finir, les personnes doivent énoncer les tâches qu'elles n'ont pas pu finir et expliquer leur blocages. Ce dernier sera analysé en équipe afin de déterminer comment y réagir, que ce soit en divisant la tâche en plusieurs ou en apportant de l'aide de la part d'autres équipes travaillant sur le projet. Dans un monde idéal, cette étape n'arrive pas car les blocages ont pu être anticipés et gérés durant les dailies.
## Canaux de communication
### Whatsapp
Nous avons établi un groupe sur Whatsapp pour avoir un canal permettant d'atteindre tout le monde simplement. Ce canal sert donc de flux général pour communiquer sur le projet et sur l'organisation (annonce d'absence ou autres).
### Discord
Le canal Discord sert, quand à lui, à avoir des canaux dédiés aux équipes et au travail. Nous avons pris cette organisation pour que le groupe Whatsapp ne se fasse pas flood et qu'il n'y ait pas de discussions sur certaines tâches qui soient entrecoupées. Nous y avons aussi fait un chat général, mais tout le monde n'étant pas habitué à utiliser Discord, nous avons pensé que garder le canal Whatsapp pour ce qui est des communications globales était plus pertinent.

# Blocages et changements
## Dailies
- Au début nous nous éternisions beaucoup car tout le monde voulait raconter la tâche qu'iel effectuait, pour cela nous avons dû adapter les dailies et raccourcir le temps de parole à 1 minute par personne maximum. Cela nous a permit de passer de 30-40 minutes à 15 minutes maximum. Si une personne souhaitait faire part de quelque chose à quelqu'un, celle-ci le faisait à la fin et uniquement aux personnes concernées afin de ne pas monopoliser le temps de toute l'équipe.
## Gestion de projet
- Il a fallu rappeler plusieurs fois le processus de création et de gestion des tâches car les membres de l'équipe travaillaient mais ne touchaient pas au tableau Kanban malgré l'existence d'une documentation ce qui engendrait des tâches sans détails ou n'ayant pas le bon statut. Cela s'est amélioré au fur et à mesure.
- Les collaborateurices avaient du mal avec les équipes au début car iels se considéraient dans une équipe fixe. Il a donc fallu adapter en n'y affectant que les "chefs d'équipes" qui y sont fidèles afin de toujours savoir ce qu'il se passe au sein de chaque secteur. Cela a permit aux différentes personnes (hors-chefs) de ne plus se considérer comme membre d'une seule équipe et donc de travailler sur différentes tâches de divers secteurs au fur et à mesure du projet.
- Au début, nous voulions faire des user stories qui se faisaient convertir par la suite en tâches. Cependant, les user stories générées étaient plus de l'ordre du concept que de la user story réaliste ce qui faisait qu'il était impossible d'en générer une tâche. Pour y remédier, nous avons décidé de passer directement à la génération de tâches ce qui donne le workflow suivant: les membres de l'équipe créent des tâches au fur et à mesure du sprint, ensuite le PO y rajoute les tâches nécessaires et n'étant pas présentes et les ordre par priorité, pour finir le Scrum Master se charge de voir la taille des tâches en story points avec le chef de chaque équipe concernée et met dans la colonne to-do le nombre de tâches réalisables et/ou nécessaires en fonction de la vitesse en story points de l'équipe afin que l'équipe ait toujours de quoi faire de manière réaliste.