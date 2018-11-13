![Git](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)
# Repo de présentation de l'utilisation de **git**
Le cours consiste à savoir :




1. Utiliser les commandes Git
2. Utilisier GitHub en collaboration



# Quelques commandes utiles :

`git init` 
> Initialise le projet

`git add .`
> ajoute toutes les modifications à l'index

`git commit -m "message"` 
> commit les modifications

##### Ajout de la commande : Modifier le dernier commit
Cette opération **n'est pas sans conséquence** car elle modifie l'historique. Modifier un commit signifie que l'on va créer un nouveau commit.
>git commit -a --amend -m "Amend commit"