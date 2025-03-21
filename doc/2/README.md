

![Illustration](src/image.webp)

# ✍️ Comment poster un article dans la doc

## 🤔 Quoicoubeh ?


Pour publier un article, tu dois d'abord te [connecter au dépôt collectif](/1) puis te rendre dans le dossier `/doc`.

Une fois dedans, tu verras une structure de fichiers et dossiers similaire à ceci :

```
/doc
│
├── index.html
├── README.md
├── src
│   └── image.webp
│
├── /1
│   ├── index.html
│   ├── README.md
│   └── src
│       └── image.webp
│
├── /2
│   ├── index.html
│   ├── README.md
│   └── src
│       └── image.webp
│
├── ...
│
└── /model
    ├── index.html
    ├── README.md
    └── src
        └── image.png
```

Quand on se connecte à [doc.lesloulous.dev](https://doc.lesloulous.dev), le site charge automatiquement l' `index.html` présent dans `/doc`, qui lit ensuite le `README.md` et l'affiche à l'écran.

Le fichier `README.md` est écrit en **Markdown**, un format très simple pour mettre du texte en forme sans se prendre la tête.
Par exemple, tu peux y :
- Ajouter des **images** 🖼️ à partir d’un lien,
- Intégrer directement du **code HTML** si tu préfères.

## 📚 Créer un article

Pour accéder à un article, l'on utilise ce genre d'URL : `doc.lesloulous.dev/nomDuDossier`

Pour créer ton propre article, copie le dossier `/model` et renomme-le comme tu veux.

Il ne te reste plus cas modifier `README.md` comme tu le veut.

## 📂 Ajouter des médias (images, vidéos, etc.)

Si tu veux ajouter des médias, place-les dans le dossier `/src` de ton article, puis indique le chemin dans le `README.md`.

**Exemple :**
```md
![Mon image](src/image.webp)
```

Tous les médias doivent être stockés dans le dossier `/src` du dossier de ton article 🗂️.

## 🎉 Fin

Voila c'est tous, une foi que tu aurra push t'es modif sur le master, quelque seconde plus tard, le site serra mis a jour.

Bonne rédaction ! ✨

