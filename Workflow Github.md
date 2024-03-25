## Créer une nouvelle tache 
1. Dans le [projet GitHub](https://github.com/orgs/C-Super/projects/1), créer une nouvelle issue avec le bouton au bas des colonnes ![workflow_1](workflow_1.png)
2. Dans la barre qui apparaît, tapez un dièse et sélectionnez "couleur3".![workflow_2](workflow_2.png)
3. Cliquez sur "create new issue"![workflow_3](workflow_3.png)
4. Entrez les informations de la tâche.![workflow_4](workflow_4.png)
5. Cliquez sur le titre de la nouvelle issue dans le projet pour afficher les details, et compléter avec les informations manquantes (**ne pas oublier les dates pour le Gantt**, ainsi que l'iteration qui correspond au sprint).![workflow_5](workflow_5.png)
6. La tâche peut maintenant être gérée dans le Kanban board sans problème. 
## Créer une branche pour la tâche
1. Rendez vous sur la page de l'issue, en cliquant sur le titre dans le détails, le lien en bas à droite, ou simplement par la liste des issues. ![workflow_6](workflow_6.png)
2. Cliquez sur ce bouton pour créer une nouvelle branche. ![workflow_7](workflow_7.png)
3. Nommer la branche d'après les conventions de sous-branche: 
	- `documentation/nom-de-branche` pour ce qui est de la documentation
	- `bugfix/nom-de-branche`  
	- `feature/nom-de-branche` 
![workflow_8](workflow_8.png)
4. Vous pouvez désormais travailler sur la branche. 
## Finir la tâche
1. Une fois que vous avez fini votre travail sur la tâche en cours, naviguez sur la page des [pull requests](https://github.com/C-Super/couleur3/pulls), et créez-en une nouvelle.![workflow_9](workflow_9.png)
2. Dans le choix de branche "compare", trouver la branche sur laquelle vous travailliez.![workflow_10](workflow_10.png)
3. Si tout semble bon, créez la pull request.![workflow_11](workflow_11.png)
4. Complétez les informations du pull request. Veillez spécialement à configurer un ou plusieurs "reviewer" pertinents qui doivent valider vos changements pour pouvoir les merge au main.![workflow_12](workflow_12.png)
5. Dans la vue du projet, déplacer l'issue dans la colonne "In Review", et attendre que le reviewer accepte la pull request :) ![workflow_13](workflow_13.png)
6. Une fois la PR acceptée, lancer le merge.![workflow_14](workflow_14.png)
7. Youpi, c'est fini. Typiquement, il faut maintenant juste effacer la branche. ![workflow_15](workflow_15.png)