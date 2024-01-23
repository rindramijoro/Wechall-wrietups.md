# Pour le write-up qui suit, je vais utiliser ">" pour indiquer le chemin a suivre

## Level 0
cd /home/level > cd 00_welcome > cat README.md .

La solution du premier level se trouve dans ce README.

## Level 1
cd (Pour revenir au tout debut) >
cd /home/level > cd 01_choice_tree > cd blue > cd hats > cd grey > cd solution > cd patience > cat SOLUTION.txt .

La solution pour ce level se trove dans ce fichier txt.

## Level 2
cd /home/level > cd 02 > ls -al > cd .porb > ls -al > cat .solution .

La solution pour level 02 se trouve dans ce ".solution".

- ls -al permet d'afficher tout les fichiers sans exception

## Level 3
cd /home/level > cd 03 > ls -al > cat .bash_history .

La solution du level se trouve dans ce ".bash_history".

## Level 4
Pour ce level, on ne fait pas "cd /home/level" mais "cd" seulement pour retourner à notre "~".

cd > cd level > cd 04_kwisatz > quand on fait "ls" dans ce directory, il y a un deux fichiers README et la solution se trouve dans le README2.md, mais ce fichier necessite un accès particulier, donc on fait chmod +751 pour pouvoir y accedre et trouver la solution.

- chmod +751 donne un accès drwxr-x--x à l'utilisateur qui va lui permettre d'executer et de lire le fichier

## Level 5
cd /home/level > cd 05_privacy > ls > cat README.md

La solution pour ce level se trouve dans ce README.md


