
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
