# Vous venez d'installer Git Bash, bravo, maintenant il faut le configurer.

Git a besoin de savoir qui vous êtes, pour cela, git donne accès à l'argument `config` pour ajouter ces informations.

### Name

> Ajoutez votre nom ou nom d'utilisateur avec la commande :

`git config --global user.name "nom_utilisateur/nom"`

### Adresse email

> Ajoutez aussi votre adresse email avec cette commande :

`git config --global user.email "je_ne_sais_quoi@domaine.extension"`

### Liste ce que vous avez écrit lors des précédentes étapes

> Vous avez accès à ce que vous avez enregistré en utilisant la commande :

`git config --global --list`

_À savoir que vous pouvez changer ces donnée localement, si l'ordinateur est partagé entre plusieurs personnes.<br>Au lieu de `--global`, utilisez `--local`.<br><br>Il faut faire les 2 premières étapes sur chaque nouvelle installation de Git Bash_
