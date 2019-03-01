# Labo Gen 01

## Guillaume Laubsher et Rémy Vuagniaux

## But

Nous devons nous entrainener a manipuler les commande git.
Et pour cela nous ferons des push de ce fichier modifier.

## Etape 1 Clone du repo

git clone ssh://git@github.com/UncleBen420/Labo01Gen_Vuagniaux_Laubsher.git

## Etape 2 premier push

echo "" >> readme.md

git status // affiche le status des fichiers modifies

git add * // ajoute les fichiers

git status // on verifie l'etat des fichiers

git commit -m "etape1" // on ajoute un commit des modifications

git push // on push les modifications sur github

## Etape 3

git status // affiche le status des fichiers modifies (readme.md a ete modifie)

git add * // ajoute les fichiers

git status // on verifie l'etat des fichiers

git commit -m "etape3" // on ajoute un commit des modifications

git push // on push les modifications sur github

## Etape 4 on cree la branch essai

git branch essai // cree la branch mais on ne switch pas dessus

git checkout essai // on switch dessus

## Etape 5 push sur la nouvelle branch

git status // affiche le status des fichiers modifies (readme.md a ete modifie)

git add * // ajoute les fichiers

git status // on verifie l'etat des fichiers

git commit -m "etape5" // on ajoute un commit des modifications

git push // on push les modifications sur github

git push --set-upstream origin essai // donnee par le terminal car il n'y a pas de upstream branch sur github

## Etape 6 push sur essai

git status // affiche le status des fichiers modifies (readme.md a ete modifie)

git add * // ajoute les fichiers

git status // on verifie l'etat des fichiers

git commit -m "etape6" // on ajoute un commit des modifications

git push // on push les modifications sur github

## Etape 7 on cree la branch essai

git branch dev // cree la branch mais on ne switch pas dessus

<<<<<<< HEAD
=======
git push --set-upstream origin dev
>>>>>>> d380a3f

## Etape 8 push sur essai

git status // affiche le status des fichiers modifies (readme.md a ete modifie)

git add * // ajoute les fichiers

git status // on verifie l'etat des fichiers

git commit -m "etape8" // on ajoute un commit des modifications

git push // on push les modifications sur github

## Etape 9 push sur master

git checkout -f master // -f force le changement de branch

git status // affiche le status des fichiers modifies (readme.md a ete modifie)

git add * // ajoute les fichiers

git status // on verifie l'etat des fichiers

git commit -m "etape9" // on ajoute un commit des modifications

git push // on push les modifications sur github
<<<<<<< HEAD
=======
¨sethb
## Etape 10 merge essai -> master

// on a plusieurs possibilites :

git merge dev // car dev pointe sur le bon commit

git merge essai^ // car cela correspond au bon commit

git merge 9c75ac7 // merge avec le numero du commit
>>>>>>> d380a3f
