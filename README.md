# Repo Commandes Git

## Description du projet
C'est un repo pour décrire les commandes Git.

## Instruction pour l'installation
 * Pour créer ce repository en local, tapez la commande suivant :
``` shell
git init
```

 * Pour voir les dernières modifications :
``` shell
git status
```

 * Pour ajouter un fichier au futur commit :
``` shell
git add <fichier>
```

 * Pour sauvegarder les modifications ajouté dans un commit :
``` shell
git commit -m"<description>"
```

 * Faire un fichier ".gitignore". Pour ne pas inclure les "node_modules", fichier ".env".

 * Pour ajouter tous les fichiers au futur commit :
``` shell
git add * ou git add .
```

 * Pour lier le repository local au distant :
``` shell
git remote add origin <url https du repository distant>
```

 * Faire un commit :
``` shell
git push origin master
```