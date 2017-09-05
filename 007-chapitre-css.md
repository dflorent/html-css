[← Chapitre 6 : Les liens](006-chapitre-les-liens.md)

CSS
===

Lier un fichier CSS à un document HTML
---

```html
<link rel="stylesheet" href="chemin/vers/style.css">
```

La syntaxe CSS
---

```css
selecteur {
    propriete: valeur;
    propriete: valeur;
    // etc.
}
```

Quelques selecteurs
---

### Les selecteurs de type

```php
// html
<p>...</p>

// css
p {...}
```

### Les selecteurs de classes

```php
// html
<div class="foo">...</div>

// css
.foo {...}
```

L'antisèche CSS
---

### La police

| Propriété   | Description                                                                        |
|-------------|------------------------------------------------------------------------------------|
| font-family | Détermine une (pile) police personnalisée *Ex : Helvetica, Arial, sans-serif;*     |
| font-size   | Détermine la taille de la police *Ex : 16px*                                       |
| font-weight | Détermine la graisse de la police *Ex : bold*                                      |
| font-style  | Détermine le style de la police *Ex : italic*                                      |

### Le texte

| Propriété        | Description                                                                   |
|------------------|-------------------------------------------------------------------------------|
| color            | Détermine la couleur du texte *Ex : red, #cc0, #cccc00                        |
| line-height      | Détermine l'espacement entre les lignes *Ex : 1.5, 24px                       |
| text-align       | Détermine l'alignement du texte *Ex : left, right, center                     |
| text-transform   | Détermine la casse du texte *Ex : uppercase, lowercase                        |
| text-decoration  | Détermine la décoration du texte *Ex : underline, none                        |

### Le fond

| Propriété         | Description                                                                  |
|-------------------|------------------------------------------------------------------------------|
| background-color  | Détermine la couleur de remplissage du fond                                  |
| background-image  | Détermine l'image de remplissage du fond                                     |
| background-repeat | Détermine la répétition du font *Ex : repeat, repeat-x, repeat-y, no-repeat* |

### Les bordures

| Propriété     | Description                                                                      |
|-------------  |----------------------------------------------------------------------------------|
| border-width  | Détermine l'épaisseur de la bordure                                              |
| border-style  | Détermine le style de la bordure *Ex : solid, dashed, dotted*                    |
| border-color  | Détermine la couleur de la bordure                                               |
| border-radius | Détermine le rayon de l'arrondi des bordures                                     |

### Le dimensionnement

| Propriété | Description                                                                          |
|-----------|--------------------------------------------------------------------------------------|
| height    | Détermine la hauteur d'un élément                                                    |
| width     | Détermine la largeur d'un élément                                                    |
| margin    | Détermine la marge externe d'un élément                                              |
| padding   | Détermine la marge interne d'un élément                                              |

---

[← Retour au sommaire](README.md)
