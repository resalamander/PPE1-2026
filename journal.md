# Journal de bord du projet encadré
##
## Semaine du 30/09

Pour cette séance, j'ai du classer les files .ann par années puis compter le nombre d'annotations effectuées chaque année en utilisant les commandes cat pour lire les files, grep pour séléctionner un terme, wc pour compter les nombres de mots et echo pour créer un fichier texte.

Je n'ai pas tout compris pour le compte d'annotations et je pense avoir pris en compte le nombre de bytes au lieu du nombre de headlines.. je ne suis pas sûre d'avoir compris la consigne.

J'ai utilisé les commandes cat *.ann puis wc > *.txt pour déplacer le nombre de mots voulus vers un nouveau fichier txt. Cependant je n'ai pas compris comment utiliser la commande echo puisqu'elle formate tous les fichiers txt et qu'il fallait faire la manipulation 3x et donc mettre à jour le nouveau fichier .txt.

J'ai du affiché les résultats dans le terminal un par un et ensuite copier-coller pour faire un seul message que j'ai redirigé vers le fichier txt avec la commande txt à la fin.

Pour la question 1.b, j'ai suivi la même méthode mais en utilisant l'étape avec grep pour séléctionné uniquement le nombre de locations annotées.

Le reste de l'exercice était un peu plus compliqué et j'ai du cherché plusieurs solutions en ligne, notamment les options possibles avec les commandes sort, uniq et cut.
J'ai d'abord spécifié ma lecture des fichiers avec grep Locations, puis cut, en choisissant les champs qui étaient intéressants (ici le nom des locations). Il fallait ensuite 

##
## semaine du 19/10
#exercices git corrections d'erreur

Lignes bidons à rajouter 

je sais pas quoi dire

Cette ligne doit rester après la correction 

##
copié-collé du journal oups.md:

Je suis censée utiliser ce journal de bord pour l'exercice sur les scripts bash, je crois, mais je comprends pas l'exercice 1.

J'ai écrit mon script pour afficher les locations par années sur la sortie standard (donc l'écran, j'imagine) mais mon script ne veut pas fonctionner.

pour l'instant j'ai écrit :

#!/bin/bash

cd ~/documents/Exercice1/ann

cd ./2016

grep Location *.ann | wc -l

cd ../2017

grep Location *.ann | wc -l

cd ../2018

grep Location *.ann | wc -l 

et après avoir rendu le fichier executable avec chmod +x, le terminal me dit que /bin/bash n'est pas executable.
Quand j'enlève cette ligne, le fichier n'est plus reconnu comme un script sh mais comme un texte brut même s'il est toujours en format sh.

J'ai essayé de comprendre mais je n'y arive pas, donc j'abandonne (à la première question, oui...)

#on met la ligne 'exercice git' de côté ? 

là je fais mes changements (je comprends pas trop)
