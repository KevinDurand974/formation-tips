# Petites astuces pour visual studio code :

### Ouvrir ou Cacher la console

> Cliqué sur la [x] en haut à droite de la console si ouvert

> Utilisé le raccourci `CONTROL + ù`

![ù key](https://i.imgur.com/ED1vb5B.png)

### Ajouter Git Bash à la console

_Si vous avez fait que `next` pendant l'installation de git bash, vous pouvez continué, si vous avez coché la case synchronisé git bash avec visual studio, c'est okay pour vous._

> C'est un petit peu galère mais tenez bon !<br>
> Dans un 1er temps, ouvrez les paramètres de visual studio code (il y a une petite astuce pour ouvrir rapidement en dessous)<br>
> Dans la barre de recherche, tapez `terminal integrated profiles`

_Ce qui donne ça :_<br>
![Terminal Integrated Profiles](https://i.imgur.com/atNmxbo.png)

> Cliquez sur `Edit in settings.json` par rapport au système de votre pc<br>
> Cela vous ouvre le fichier `settings.json` qui est litérallement vos paramètres.<br>
> Votre curseur est sur une ligne vide par défaut. Ajoutez :<br>

```json
"GitBash": {
  "path": "C:/Program Files/Git/bin/bash.exe"
}
```

Qui, une fois ajouté ressemble à ça :<br>
![Added Lines in settings.json](https://i.imgur.com/8Fzb4Zn.png)

_Par défaut, sur windows, c'est ce chemin_<br>
_N'hésitez pas à me dire pour MacOS et Linux_

_PS: `GitBash` = Un nom affiché dans la console, vous pouvez très bien mettre autre chose._

> Attention à bien avoir ajouté la virgule à la fin de la ligne au dessus, sans quoi il y aura une erreur.<br>
> Enregistrez le fichier. (Ctrl + s)<br>
> Vous pouvez dorénavent, sélectionné le profil `GitBash` dans votre console.

### Changer le type de Shell par défaut utilisé par la console

> Cliqué sur la [▾] à côté du [+] en haut a droite de la console

> Dernier choix de la liste, `Select Default Profile`

ou

> Cliqué sur `FILE` >> `PREFERENCES` >> `TERMINAL` >> Tapé dans la barre de recherche `terminal.integrated.defaultProfile` >> Changez selon votre plateforme

ou

> Via un raccrouci : `CONTROL + SHIFT + P` >> puis tapé `tsdp` qui est le raccourci de _Terminal: Select Default Profile_

### Accéder aux paramètres rapidement

> Via un raccourci : `CONTROL + ,`

### Synchronisez ces extensions et autres

> Vous avez pour habitude de travailler avec 50 extensions sur votre PC à la maison ?<br>
> Vous avez un autre PC à votre travail ?<br>
> Vous vous demandez comment je pourrais vite avoir le même setup qu'à la maison ?<br>
> Microsoft et un Utilisateur on pensez à vous !

1. Cliquez sur le bouton paramètre en bas à gauche, appuyer sur `Turn on Settings Sync...`

![Settings > Settings Sync](https://i.imgur.com/UbcwvnT.png)

2. Sélectionner ce que l'on veux synchronizer

![Select Sync](https://i.imgur.com/NULcFvc.png)

3. Sélectionner la méthode de synchronisation

![Select Sync](https://i.imgur.com/VcYt87T.png)

4. Autorisez VS Code à acceder à Github

![Select Sync](https://i.imgur.com/tLvVUgE.png)

5. Autorisez Github à fonctionner avec VS Code

![Select Sync](https://i.imgur.com/KP9ArLk.png)

6. Page Success affichée, début de la synchronisation sur VS Code en fond

![Select Sync](https://i.imgur.com/6vBQ5W3.png)

7. Et voilà !

_Si un problème est survenu pendant ces étapes, recommencer._<br>
_Si à la dernière étape le token n'est pas directement lié sur VS code, suivez les étapes en dessous de la page Success_

### Quelques raccourcis utiles

_À noter que `SHIFT` = `MAJ`_

> Enregistrer : `CONTROL + S`

> Enregistrer-Sous : `CONTROL + SHIFT + S`

> Nouveau Fichier : `CONTROL + N`

> Ouvrir un fichier : `CONTROL + O`

> Dupliqué une ligne (curseur sur la ligne voulu) : `SHIFT + ALT + ↓` ou `↑`

> Copier : `CONTROL + C`

> Coller : `CONTROL + V`

> Couper la selection (bien avoir une selection) : `CONTROL + X`

> Couper la ligne : `CONTROL + X`

> Selectioner les mêmes mots (une fois selectionnés) : `CONTROL + D`

> Rechercher : `CONTROL + F`

> Retour à la ligne : `ALT + Z`

> Nouvelle console : `CONTROL + SHIFT + ù`

> Multiple curseur : `ALT + CLIQUE GAUCHE`

> Ouvrir rapidement un fichier présent dans l'espace de travail : `CONTROL + E` ou `P` >> selectionnez le fichier que vous voulez

> Déplacer une ou des lignes vers le bas/haut : `ALT + ↓` ou `↑`

> Ce déplacer gràce aux symbole (arborescence) dans le fichier : `CONTROL + SHIFT + O`

> Cacher la barre latérale : `CONTROL + B`

> Fast Scrolling (Défilement rapide avec la molette) : `ALT + MOLETTE HAUT / BAS`

_D'autre raccourci : [Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf) / [MacOS](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf) / [Linux](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf)_
