# git commit

### C'est quoi ?

> `git commit` enregistre les modifications avant de les envoyer.<br>
> Il est cependant très fortement conseillé de mettre un message lors du commit, même dans le cas où il n'y a presque aucun changement.<br>
> Je vais montrer comment faire un commit sans message mais à n'utiliser vraiment s'il n'y a pas le choix.

### git commit avec un message :

> Comme dit précédemment, on utilisera 99,99% du temps `git commit` avec un message.<br>
> D'ailleurs si vous essayez de faire un commit sans message, il vous retournera une erreur.<br>
> Pour cela, on écrira comme ceci : `git commit -m "explication"`

_Par exemple :_

> `git commit -m "J'ai modifié le fichier test.html"`

> Ici, on écrit un message grâce au petit argument `-m <explication>` qui est le raccourci de `--message=<explication>`.

_PS: faire un `git commit -m ""` vous renverra une erreur._

### git commit sans message :

> Très déconseillé, mais existant pour des cas particulié.<br>
> Par cas particulié, qu'est ce que je veux dire ?<br>
> Ce commit très spécial est plutôt utilisé pour les automations par des scripts qui s'occupent d'automatiser le `add`, `commit` et `push` assez régulièrement.

_Par exemple :_

> `git commit --allow-empty-message`

> Comme écrit, on ajoute un paramètre qui "autorise" à faire le commit sans message.
