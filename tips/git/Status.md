# git status

### C'est quoi ?

> `git status` demande à git ce qui se passe actuellement.<br>Cet argument vous dira si il y a eu des changements qui n'ont pas été "add" et / ou "commit", si des fichiers ne sont pas "tracker" (suivi). On peu y voir aussi des commandes à faire.

**Par exemple :**

![Git Status Full](https://i.imgur.com/r50tqBn.png)

On a donc un `git status` qui nous dit pleins de choses.

_Dans un 1er temps on va ce concentrer sur la partie du haut et dans un second temps la partie basse._

<hr>

### Partie Haute :

![Git Status Top Part](https://i.imgur.com/H5hGEvH.png)

**1ère ligne**<br>

> "On branch master"<br>
> Qui veut dire: "Vous êtes sur la branche master (principal par défaut)"

**2ième ligne jusqu'à la fin**<br>

> "Changes not staged for commit"<br>
> Qui veut dire : "Des changements on été apportés mais n'ont pas été ajoutés pour pouvoir commit"<br><br>
> Elle vous indique donc qu'il faut utilisé `git add <file>` pour mettre à jour et pouvoir commit après.<br>
> Elle vous indique aussi que vous pouvez annuler ces changements en utilisant `git restore <file>`.<br><br>
> Pour finir, elle vous affiche en rouge le ou les fichiers / dossiers concernés.

<hr>

### Partie Basse :

![Git Status Bottom Part](https://i.imgur.com/dfx6rL1.png)

**1ère ligne jusqu'à l'avant dernière**

> "Untracked files"<br>
> Qui veut dire : "Fichiers non suivis"<br>
> Elle vous indique donc qu'il faut utilisé `git add <file>` pour les inclures et pouvoir commit après.<br>
> Pour finir, elle vous affiche en rouge le ou les fichiers / dossiers concernés.

**_Dernère ligne_**

> "No changes added to commit"<br>
> Veut dire qu'aucuns changements n'a été ajoutés pour commit dernière.<br>
> Elle propose ensuite ces 2 commandes.

_N'hésitez pas à abuser de `git status`._
