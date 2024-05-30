Je kunt de hoeken van een element afgerond maken met de 'rounded' class.

![Drie tegels op een webpagina, elk met afgeronde hoeken.](images/rounded.PNG)

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<div class="rounded">
    <p>Voeg hier tekst toe.</p>
</div>

--- /code ---

**Tip:** Je kunt de `border-radius` van de class `rounded` aanpassen in `style.css`.

--- code ---
---
language: CSS
filename: style.css
line_numbers: false
---

.rounded {
  border-radius: 1rem;
}

--- /code ---
