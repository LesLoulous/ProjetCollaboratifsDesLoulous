

<!-- ![Example image](src/image.webp) -->
<img src="src/image.webp">


# Comment utiliser le dépôt collectif 

## 1. Récupérer le dépôt collectif
Tout d'abord, tu dois cloner le dépôt collectif en local avec la commande suivante :

```sh
git clone https://github.com/LesLoulous/ProjetCollaboratifsDesLoulous.git
```

## 2. Se déplacer sur la branche `dev`
Après le clonage, bascule sur la branche de développement (`dev`) :

```sh
git checkout origin/dev
```

## 3. Créer et aller sur ta branche perso
Crée et bascule directement sur ta propre branche à partir de `dev`. Remplace `MYNAME` par ton pseudo :

```sh
git checkout -b dev-MYNAME
```

## 4. Envoyer ta branche perso sur le dépôt collectif
Enfin, pousse ta nouvelle branche vers le dépôt distant pour la rendre accessible aux autres :

```sh
git push origin dev-MYNAME
```

Ta branche est maintenant disponible sur le dépôt collectif, et tu peux commencer à travailler dessus ! 🎉

## ℹ️ Astuce
Pour visualiser toutes les branches disponibles sur le dépôt github, utilise la commande suivante :

```sh
git branch -r
```