# G404_TP-Fil-Rouge_BOOKMAKER
TP qui court sur toute la formation, avec plusieurs refactorisations (de la POO vanilla à la création d'une API) // Repo avec dossiers front et back


# Commandes pour sous-modules

Cloner un projet contenant des sous-modules permet d'obtenir les différents répertoires mais vide.
Il faut executer les deux **commandes** suivantes :

```bash
git submodule init
```

```bash
 git submodule update
```
**OU** passer l'option recurse à la commande git clone (suivi donc de l'url du répo)

```bash
 git clone --recurse-submodules
```
