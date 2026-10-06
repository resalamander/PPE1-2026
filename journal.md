# Journal de bord du projet encadré
##
# Semaine du 30/09

Pour cette séance, j'ai du classer les files .ann par années puis compter le nombre d'annotations effectuées chaque année en utilisant les commandes cat pour lire les files, grep pour séléctionner un terme, wc pour compter les nombres de mots et echo pour créer un fichier texte.

Je n'ai pas tout compris pour le compte d'annotations et je pense avoir pris en compte le nombre de bytes au lieu du nombre de headlines.. je ne suis pas sûre d'avoir compris la consigne.

J'ai utilisé les commandes cat *.ann puis wc > *.txt pour déplacer le nombre de mots voulus vers un nouveau fichier txt. Cependant je n'ai pas compris comment utiliser la commande echo puisqu'elle formate tous les fichiers txt et qu'il fallait faire la manipulation 3x et donc mettre à jour le nouveau fichier .txt.
-
J'ai du affiché les résultats dans le terminal un par un et ensuite copier-coller pour faire un seul message que j'ai redirigé vers le fichier txt avec la commande txt à la fin.

Pour la question 1.b, j'ai suivi la même méthode mais en utilisant l'étape avec grep pour séléctionné uniquement le nombre de locations annotées.

Le reste de l'exercice était un peu plus compliqué et j'ai du cherché plusieurs solutions en ligne, notamment les options possibles avec les commandes sort, uniq et cut.
J'ai d'abord spécifié ma lecture des fichiers avec grep Locations, puis cut, en choisissant les champs qui étaient intéressants (ici le nom des locations). Il fallait ensuite 

