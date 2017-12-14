# html css

## html

Voir la page `index.html` avec un navigateur dans windows :

    http://localhost/wis-b1-html-css-2017-2018/

Voir la page `index.html` avec un navigateur dans macos :

    http://localhost:8888/wis-b1-html-css-2017-2018/

Le doctype html5 :

    <!DOCTYPE html>

Les balises ouvrantes :

    <balise>

Attention : les balises ouvrantes doivent toujours être refermées par après.

Les balises fermantes :

    </balise>

Les balises auto-fermantes :

    <balise />

Les attributs :

    <balise1 attribut="valeur"></balise1>
    <balise2 attribut="valeur" />

Les attributs booléens :

    <balise1 attribut></balise1>
    <balise2 attribut />

## chemins

Les chemins :

- un chemin absolu commence par un `/` (ou un nom de disque sur windows).
- le dossier en cours est désigné par `./`.
- le dossier parent est désigné par `../`.

## css

La syntaxe :

    /* commentaire */
    sélecteur {
      propriété1: valeur1;
      propriété2: valeur2;
    }

Le sélecteur par balise :

    p {
      background-color: pink;
    }

Le sélecteur par `class` :

    .my-class {
      background-color: pink;
    }

Le sélecteur par `id` :

    #my-item {
      background-color: pink;
    }

## npm

Vérifier la version de npm :

    npm -v

Initialiser un projet :

    npm init -y

Installer jquery :

    npm install -S jquery

Installer bootstrap :

    npm install -S bootstrap

## débogguer une page web

- appuyer sur la touche F12 pour afficher la console de développement.
- aller sur l'onglet réseau (network)
- vérifier que les fichiers des balises `link` et `script` sont présents dans la liste
- vérifier que les fichiers ont un code http 200 (téléchargé) ou 304 (déjà téléchargé)

Un code 404 indique un fichier non trouvé. Il faut donc corriger le chemin qui pointe sur le fichier.

Attention : c'est `bootstrap` et non `boostrap` !

## doc

- https://developer.mozilla.org/en-US/docs/Web/HTML/Element
- https://developer.mozilla.org/en-US/docs/Web/CSS/Reference

## resources

- [The W3C Markup Validation Service](https://validator.w3.org/)
- [Service de validation CSS du W3C](https://jigsaw.w3.org/css-validator/)
- https://fonts.google.com/
- https://iconmonstr.com/
- http://fontawesome.io/
- https://css-tricks.com/
- https://css-tricks.com/couple-takes-sticky-footer/
- https://choosealicense.com/
- http://creativecommons.fr/

## aller plus loin

- htmltidy
