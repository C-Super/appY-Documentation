La gestion de projet est un élément crucial pour que le projet se déroule sans accro, surtout lorsque l'on est sur une méthodologie agile car il faut que les processus soient clairs pour que tout le monde comprenne quoi faire et comment le faire.
## Organisation
Pour ce qui est de l'organisation, nous avons commencé le projet par prévoir les différentes équipes dont nous aurions besoin et d'y affecter des personnes par préférence.

Cependant, étant tous des ingénieurs des médias avec des capacités relativement similaires, ces équipes sont une base et non une structure dure. Tout le monde peut aider ou avoir envie de faire autre chose à un moment où à un autre. L'utilité de ces affectations est de toujours avoir des personnes de contact si un membre de l'équipe d'un autre secteur a une interrogation sur un domaine sur lequel il n'a pas collaboré.

![[repartitionEquipes.jpg]]
## Mise en place de la gestion de projet agile
### Sprint planning
Le Sprint Planning est le première étape, elle se fait en début de Sprint afin de l'initier. Pour se faire il faut respecter plusieurs étapes.

Tout d'abord le Product Owner doit trier le backlog contenant les User Stories par priorité afin de faire connaître au Scrum Master les tâches à réaliser et leur pertinence. Cela permet de mieux s'organiser pour avoir un livrable correspondant aux attentes et aux impératives du client en fin de Sprint.

Ensuite, le Scrum Master réalise les issues (tâches) à faire et passe vers les équipes travaillant sur le projet pour savoir où elles en sont. Cela permet d'analyser la situation et de gérer les cas de tâches bloquantes ou d'atomiser et de répartir les tâches si elles prennent plus de temps que prévu.
En fonction de la vélocité de l'équipe et des tâches en cours, le Scrum Master doit ensuite passer les tâches de "backlog" à "to-do" pour pouvoir garantir une charge constante et réalisable sur l'équipe.

Pour finir, le Product Owner réorganise la priorité des tâches en fonction des modifications afin de déterminer les tâches importantes à faire si l'équipe a un gain en vélocité.
### Tableau Kanban
Pour ce qui est du tableau Kanban, nous avons choisi d'utiliser [Github Project](https://docs.github.com/fr/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) car il permet d'affecter des issues aux tâches et d'avoir constamment un lien sur les branches Git. Cette solution semble être particulièrement optimale en ce qui concerne le développement, mais nous avons pris des décisions pour y intégrer la documentation et les autres tâches en général.
En effet, pour alléger la tâche des personnes rédigeant le rapport, il est bien plus simple d'avoir un format de texte brut à copier/coller. C'est pour cela que nous avons choisi de faire le rapport en markdown sur [Obsidian](https://obsidian.md/). Cela nous permet aussi d'intégrer le rapport et de le review simplement dans Github au lieu de passer par des éditeurs de texte classiques qui peuvent complexifier le travail.

Pour ce qui est des reviews, nous avons bloqué le push sur la branche main de Github ce qui oblige les équipes à faire des issues pour chaque tâche. Cette méthodologie oblige une autre personne à review le travail de la première, ce qui nous permet d'avoir constamment un regard critique et nouveau sur le travail et nous permet de remonter des choses qui ne vont pas plus efficacement.
Cela permet aussi aux membres de l'équipe de review des tâches à des moments où ces derniers sont moins productifs, afin de toujours avoir quelque chose de différent à faire et de pouvoir changer de tâche afin de ne pas fixer un écran blanc.
### Dailies
Les dailies ont lieu tous les jours à 10h du matin et doivent durer entre 30 et 40 minutes maximum. Leur but n'est pas de constater le travail effectué en faisant la police mais d'annoncer des blocages et de trouver des solutions ou de partager des visions différentes sur ce qui a été fait.

Toute demande qui n'a pas été prévue dans la projet, que ce soit de l'ordre de la collaboration ou de la demande de matériel, doit être faite à ce moment là de préférence.
Des PV sont établis sur toutes les dailies afin de pouvoir retracer les changements et les spécifications demandées ou annoncées.
### Sprint rétrospectives
Les rétrospectives sont la dernière étape d'un sprint. Pour que tout se passe bien, nous avons établi un processus clair.

Premièrement, les personnes annoncent le travail effectué et en font de préférence des démonstrations afin de pouvoir peut-être soulever des questions.

Ensuite, nous utilisons [RetroTool](https://retrotool.io/) qui est un outil en ligne, permettant d'émettre trois types de réactions différentes:
1. Les "start" sont des idées qui pourraient résoudre, débloquer ou améliorer le processus de travail global
2. Les "stop" sont des choses qu'il faut impérativement arrêter de faire afin d'optimiser la productivité sur le projet
3. Les "continue" sont des idées qui ont été apportée en cours de projet et qui seraient intéressantes à intégrer afin d'améliorer la productivité sur le projet

Pour finir, les personnes doivent énoncer les tâches qu'elles n'ont pas pu finir et expliquer leur blocages. Ce dernier sera analysé en équipe afin de déterminer comment y réagir, que ce soit en divisant la tâche en plusieurs ou en apportant de l'aide de la part d'autres équipes travaillant sur le projet. Dans un monde idéal, cette étape n'arrive pas car les blocages ont pu être anticipés et gérés durant les dailies.
## Canaux de communication
### Whatsapp
Nous avons établi un groupe sur Whatsapp pour avoir un canal permettant d'atteindre tout le monde simplement. Ce canal sert donc de flux général pour communiquer sur le projet et sur l'organisation (annonce d'absence ou autres).
### Discord
Le canal Discord sert, quand à lui, à avoir des canaux dédiés aux équipes et au travail. Nous avons pris cette organisation pour que le groupe Whatsapp ne se fasse pas flood et qu'il n'y ait pas de discussions sur certaines tâches qui soient entrecoupées. Nous y avons aussi fait un chat général, mais tout le monde n'étant pas habitué à utiliser Discord, nous avons pensé que garder le canal Whatsapp pour ce qui est des communications globales était plus pertinent.