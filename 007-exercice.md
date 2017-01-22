Introduction à CSS
---

### La syntaxe

```css
selecteur {
    propriété: valeur;
    propriété: valeur;
    // etc.
}
```

### Quelques selecteurs

#### Les selecteurs de type

```php
// html
<p>...</p>

// css
p {...}
```

#### Les selecteurs de classes

```php
// html
<div class="foo">...</div>

// css
.foo {...}
```

### Lier un fichier CSS à un document HTML

```html
<link rel="stylesheet" href="chemin/vers/style.css">
```

Ex7
---

1. Créer un dossier `css` dans le dossier `html-css`
2. Créer un ficher `style.css` dans le dossier `css`
3. Editez le fichier `style.css` avec votre éditeur de texte
4. Copiez-Collez les lignes suivantes dans `style.css` :

```css
body {
    color: #333;
    font-family: sans-serif;
    font-size: 14px;
    line-height: 1.6;
}
```

5. Sauvegardez, rafraichissez

Ressource
---

http://cssreference.io/

[Ex8](008-exercice.md)
