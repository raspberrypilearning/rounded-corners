Pour arrondir les coins d'un élément, tu peux utiliser la classe 'rounded'.

![Trois tuiles sur une page web, chacune avec des coins arrondis.](images/rounded.PNG)

## --- code ---

language: html
filename: index.html
line_numbers: false
--------------------------------------------------------

<div class="rounded">
    <p>Ajoute du texte ici.</p>
</div>

\--- /code ---

**Astuce :** tu peux ajuster le `border-radius` de la classe `rounded` dans `style.css`.

## --- code ---

language: CSS
filename: style.css
line_numbers: false
--------------------------------------------------------

.rounded {
border-radius: 1rem;
}

\--- /code ---
