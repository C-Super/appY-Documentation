
## Contexte

Ce test d'utilisabilité est effectué pour l'application Appy, qui propose des balades en famille organisées en mode parcours. Les utilisateurs peuvent sélectionner des parcours, obtenir des informations détaillées et suivre des itinéraires guidés.

## But

Le but des tests utilisateurs serait de vérifier si les tâches définies sont réalisables et conviviales pour les utilisateurs. Cela aiderait à comprendre comment les utilisateurs interagissent avec l'application et à identifier les éventuels problèmes ou obstacles qu'ils pourraient rencontrer lors de l'exécution des tâches spécifiques.

## Méthode

Nous avons effectué un test d’utilisabilité. Ce type de tests consistent à donner un certain nombre de tâches à un testeur. Le testeur doit effectuer les tâches tout en décrivant ses actions et ses pensées(technique de la pensée à voix haute).

Un facilitateur est présent pour guider le testeur tout au long du test. Son rôle est d’encourager le testeur à développer ses réflexions au sujet ses actions, et éventuellement lui apporter de l’aide s’il se retrouve bloqué.

## Instructions

Bonjour …

Présentation …

Avant de commencer, j’ai quelques informations pour vous, et je vais les lire afin de m’assurer de tout couvrir.

Nous demandons à des personnes d’essayer d’utiliser l’application appY sur lequel nous travaillons, pour voir si tout fonctionne comme imaginé. Cette session devrait prendre environ 30 minutes. 

La première chose que je veux directement mettre au clair : nous testons appY, pas vous. Vous ne pouvez pas vous tromper. En fait, c'est probablement le seul endroit aujourd'hui où vous ne devez pas vous soucier de faire des erreurs. 

Pendant l'utilisation l’application, je vais vous demander le plus possible d'essayer de penser à voix haute: dire ce que vous regardez, ce que vous essayez de faire et ce que vous pensez. Ce sera d’une grande aide pour nous. 

Si vous avez des questions en cours de route, posez-les. Je ne pourrais peut-être pas y répondre tout de suite, car nous sommes intéressés de savoir comment vous feriez si personne n’était à côté de vous pour vous aider. Mais si vous avez toujours des questions lorsque nous aurons terminé, j’essaierais alors d’y répondre. Et si vous avez besoin de faire une pause à tout moment, dites-le-moi.

Si besoin d’enregistrer demander le consentement de la personne et lui faire signer un papier

## Questions

OK. Avant de nous rendre sur l’application appY , je souhaiterais vous poser quelques petites questions. 

D’abord, quelle est votre occupation dans la vie 

Est-ce que vous faites des sorties en familles ? 

Quel type de sorties faites-vous ?  

Connaissez-vous bien la ville d’Yverdon-les-Bains? 

OK, parfait. Nous avons fini avec les questions, et nous pouvons commencer à jeter un œil sur l’application.

### Tache 0

Vous êtes sur l'application explorer la et indiquez son utilité.

Hypothèse : l’utilisateur va explorer l’application et comprendre l’utilité et faire des retours

Temps : 1 min
#### Critères de réussite :

·        Identifier clairement l'objectif principal de l'application.

·        Comprendre les fonctionnalités principales offertes par l'application.

·        Être en mesure d'expliquer de manière concise l'utilité de l'application.

#### SEQ
![[SEQ.png]]
### Tache 1 

Vous aimeriez effectuer une balade avec vos enfants, vous décidez de commencer le parcours pierre de joie.

Facilitateur : Aider à comprendre qu’il doit réaliser la balade. Il va arriver sur Google maps lui dire que c’est car vous êtres trop loin du parcours.  Si la personne le comprend ne pas aider.

Hypothèse : l’utilisateur pourrait ne pas comprendre comment débuter la balade ainsi que sur Google maps sur le fait que l’utilisateur est trop loin pour commencer.

Temps : 3-5 min

#### Critères de réussite :

·        Sélectionner le parcours Pierre de Joie dans l'application de cartographie.

·        Obtenir des indications claires sur le point de départ et l'itinéraire du parcours.

#### SEQ

![[SEQ.png]]
### Tache 2

Vous êtes au café du milieu quelques jours plus tard, vous vous souvenez avoir obtenu un bon pour ce café grâce au parcours Pierre de Joie. Vous décidez de l'utiliser lorsque vous recevrez l'addition.

Facilitateur : Aider l’utilisateur si besoin sans lui donner les réponses, l’aiguiller, lui demander pourquoi il ne comprend pas

Hypothèse : l’utilisateur va trouver ou sont enregistré les bons, mais pourrait ne pas savoir comment l’utiliser

Temps : 1-3 min

#### Critères de réussite :

·        Trouver ou sont enregistrées les bons dans l’application

·        Présenter le bon pour le paiement de l'addition

#### SEQ
![[SEQ.png]]
### Tache 3

Vous êtes chez vous et votre enfant vous parle de la balade que vous avez faite la semaine passée, la pierre de joie. Il/, elle vous pose des questions et vous décidez de lui lire l’histoire dédiée.

Facilitateur : Aider l’utilisateur si besoin sans lui donner les réponses, l’aiguiller, lui demander pourquoi il ne comprend pas

Hypothèse : l’utilisateur va chercher dans le parcours  l’histoire de la pierre de joie ou l’utilisateur va trouver l’onglet histoire.

Temps : 2-3 min 

#### Critères de réussite :

·        Trouver l'histoire associée au parcours Pierre de Joie.

·        Commencer à lire

#### SEQ
![[SEQ.png]]


### Améliorations des tests users 

Après le premier test et pour la suite des tests utilisateurs, bien que notre test soit pertinent, nous ferions certains changements afin d’être encore plus précis dans nos demandes et d’avoir des retours plus pertinents qui nous permettra de pousser encore plus loin nos composants interface.

Voici les points d’améliorations pertinents que nous ferons :

-            Tâche 0 : Faire la différence entre exploration et navigation et en faire deux tâches à part entière avec pour chacune des objectifs différents.

-            Tâche 1 : Cette tâche demande de faire un parcours précis. Durant ce parcours, l’utilisateur débloque un objet magique. Il faudrait lui demander quelle serait l’utilité de ce dernier.

-            Tâche 2 : On pourrait également demander lors de cette tâche, où sont les partenaires AppY.

-            Tâche 3 : Être plus précis dans notre demande pour valider la tâche et lui demander de lire le premier paragraphe de l’histoire.

-            Tâche 4 : Nouvelle tâche qui serait liée à ce qui s’est passé dans la tâche 1, et qui lui demanderait d’aller chercher l’objet gagné lors de sa balade.

-            Tâche 5 : Nouvelle tâche afin de pouvoir tester la véracité de nos filtres parcours.

Si l’utilisateur n’arrive pas à avancer dans la tâche, ajouter une sous-tâche pour la suite des tests, malgré le fait que les premiers ne l’auront pas eu. Cela ne biaise pas les informations et nous permet d’être plus pertinent sur nos changements.

A la fin, il faudrait se focaliser sur les output et leurs points principaux. Si cela n’a pas fonctionné, faire des propositions d’amélioration, grâce au diagramme urgent – critique. Si les output fonctionnent, nous y mettrons fin.

Pour notre projet, 4-5 tâches à effectuer est correcte, plus deviendrait peu pertinent.

Grâce à notre questionnaire SEQ demandé à chaque fin de tâche, nous auront une excellente vision de nos points de fixions et seront à même d’y remédier facilement.