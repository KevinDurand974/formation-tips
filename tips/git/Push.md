# git push

### C'est quoi ?

> `git push` pousse les modifications vers le dépôt en les mettants à jours.<br>
> On peu y ajouter divers arguments, on va voir ça.

<br><hr><br>

### La Base :

> `git push`

_Exemple :_

`git push`

> Met à jour le dépôt distant en y appliquant le ou les commits de la branche actuelle

<br><hr><br>

### \<branche> et <dépôt_distant> :

> `git push <dépôt_distant> <branche>`

_Exemple :_

`git push origin pending`

> On envoie le ou les commits de la branche `pending` vers le dépôt `origin` (correspond à l'url du dépôt)

<br><hr><br>

### \<branche1:branche2> et <dépôt> :

> `git push <dépôt_distant> <branche1:branche2>`

_Exemple :_

`git push origin pending:likethis`

> On envoie le ou les commits de la branche actuelle `pending` vers le dépôt `origin` en la renommant la branche en `likethis`

<br><hr><br>

### \--set-upstream, \<branche> et <dépôt> :

> `git push --set-upstream <dépôt_distant> <branche>`

_`--set-upstream` est également disponible en version courte : `-u`_

_Exemple :_

`git push -u origin pending`

> On envoie le ou les commits de la branche `pending` vers le dépôt `origin`<br>

> Lie la branche du dépôt avec la branche locale<br>Ou<br>Crée la branche sur le dépôt s'il elle n'existe pas puis la lie
