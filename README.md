# Push_swap testeur
Attention ce testeur a ete implemente pour Linux uniquement

## Utilisation
Clonez le testeur dans le repertoire ou se trouve votre Makefile
```Shell
git clone https://github.com/ldubu/push_swap_testeur.git
```
Puis rentrez dans le dossier du testeur et lancez le script
```Shell
cd push_swap_testeur
./test.sh
```
## Retour 
Pour chaque categorie le programme effectue un certain nombre de test avec un generateur de nombre aleatoire.

Pour chaque test, il affiche s'il a passe le checker et combien d'instruction votre push_swap a utilise.

Si votre programme est KO par le checker ou qu'il depsse le nombre maximum d'instruction, le testeur affiche la liste de chiffres et l'output de votre programme.

![alt text](https://github.com/ldubu/push_swap_testeur/blob/main/Screenshot/Screenshot%20from%202022-02-10%2014-28-03.png)

A la fin, il affiche un resume de vos performance et calcule une note approximative qui se base sur votre pire nombre d'instruction.

![alt text](https://github.com/ldubu/push_swap_testeur/blob/main/Screenshot/Screenshot%20from%202022-02-10%2014-27-17.png)  

## Generateur de nombre aleatoire
```Shell
cd number_generator
make
./gen
```
