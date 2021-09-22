# git clone

### C'est quoi ?

> `git clone` vous permet de répurérer n'importe quel dépôt existant sur Github (publique) en le clonant (copie).<br>
> On utilisera cette commande avec au moins 1 argument en plus, l'url du dépôt.<br>
> À savoir que depuis peu, août 2021, Github recommande très fortement d'utilisé **ssh** pour cloné les dépôt.<br>
> Vous pouvez récupérer ce lien sur Github en cliquant sur le dépôt voulu, puis code, cliquez sur ssh, copié le lien.<br>
> Celui-ci ressemblera à : `git@github.com:UTILISATEUR/NOM-DU-DEPOT.git`

![SSH Link](https://i.imgur.com/rvUCriM.png)

> Une fois cloné, cette commande vous créra un dossier du même nom.

_Si vous ne voulez pas avoir le nom du dépôt comme nom de dossier par défaut, vous pouvez passer 1 argument en plus.<br>Celui-ci étant le nom du dossier dans lequel il mettera les fichiers clonés._

> git clone ssh-url, clonera dans le dossier `formation-tips`<br>
> ![Git Clone](https://i.imgur.com/cG61naI.png)

> git clone ssh-url nom-de-dossier, clonera dans le dossier `nom-bizarre`<br>
> ![Git Clone](https://i.imgur.com/8kh19UM.png)
