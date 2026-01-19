Il contient quelques indices pour remplir les fichier html, css, etc pour que vous puissiez vous concentrer sur la gestion des version du projet

# CONTENU CV

Diviser votre CV en plusieurs sections, faites au moins un commit par section (avec un titre de message comme "Ajoute ma formation")

## Information personnelle

- Ajouter des éléments sur votre nom, prénom
- vous pouvez ajouter un lien avec votre email
  ```html
  <a href="mailto:monemail@estia.fr">monemail@estia.fr</a>
  ```
- vous pouvez ajouter votre numéro de téléphone
  ```html
  <a href="tel:+330605040302">06 05 04 03 02</a>
  ```
- Ajouter votre photo de profil
  ```html
  <img src="monimage.jpg" alt="Photo de profil de X" />
  ```
  N'oublier pas d'ajouter _monimage.jpg_ au projet
- Ajouter votre adresse postale
  ```html
  <p>Mon adresse</p>
  ```

## Formation / Education

Ajouter une liste avec vos formations

```html
<ul>
  <li><span> Formation 1 </span> <span> 2019-2020 </span></li>
  <li><span> Formation 2 </span> <span> 2018-2019 </span></li>
  <li><span> Formation 3 </span> <span> 2017-2018 </span></li>
</ul>
```

## Experience

Ajouter une liste avec vos expériences professionnelles

```html
<ul>
  <li><span> Experience 1 </span> <span> 2019-2020 </span></li>
  <li><span> Experience 2 </span> <span> 2018-2019 </span></li>
  <li><span> Experience 3 </span> <span> 2017-2018 </span></li>
</ul>
```

## Etc

# HTML : Structure du document

## Insérer un fichier CSS

```html
<link rel="stylesheet" href="css/style.css" />
```

## Insérer une image

```html
<img src="img/monimage.jpg" alt="Description de l'image" />
```

## Insérer un lien

```html
<a href="https://www.google.fr">Google</a>
```

## Créer une section

    ```html
    <section>
        <h2>Titre de la section</h2>
        <p>Contenu de la section</p>
    </section>
    ```

## Créer une liste

    ```html
    <ul>
        <li>Element 1</li>
        <li>Element 2</li>
        <li>Element 3</li>
    </ul>
    ```

## Ajouter une classe

        ```html
        <section>
            <h2>Titre de la section</h2>
            <p class="Highlight">Contenu de la section</p>
        </section>
        ```

## Ajouter un id

        ```html
        <section id="Focus">
            <h2>Titre de la section</h2>
            <p>Contenu de la section</p>
        </section>
        ```

# PROJET

Vous pouvez structurez votre projet comme suit

```
.
├── README.md
├── index.html
├── css
│   └── style.css
└── img
    └── monimage.jpg
```

# CSS

## Selectionner des éléments

### Selectionner tous les éléments d'un type

```css
p {
  /* style */
}
```

### Selectionner un élément par son id

```css
#Focus {
  /* style */
  border: 1px solid #ff0000;
}
```

### Selectionner un élément par sa classe

```css
.Highlight {
  /* style */
  background-color: #ffff00;
  font-weight: bold;
}
```

### Selectionner un élément par sa position

```css
span:first-child {
  /* style du premier span d'un élément, par exemple le nom de la formation  */
}

span:last-child {
  /* style du dernier span d'un élément, par exemple la date dans la éléments de la liste formation */
}
```

## Style

### Couleur de fond

```css
body {
  background-color: #000000;
}
```

### Couleur de texte

```css
p {
  color: #ffffff;
}
```

### Taille de texte

```css
p {
  font-size: 1.5em;
}
```

### Police de texte

```css
p {
  font-family: Arial, Helvetica, sans-serif;
}
```
