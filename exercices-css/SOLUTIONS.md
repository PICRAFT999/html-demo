# 🔑 Solutions des exercices CSS

> **Note pour l'oncle/tante** : Ces solutions sont là pour vous aider à guider Raphaël s'il est bloqué. Encouragez-le à essayer lui-même avant de regarder !

## Exercice 01 - Premiers pas

```css
h1 {
    color: blue;
}

p {
    color: green;
    font-size: 20px;
}
```

---

## Exercice 02 - Couleurs de fond

```css
body {
    background-color: lightgreen;
}

h1 {
    background-color: brown;
    color: white;
    padding: 10px;
}
```

---

## Exercice 03 - Listes

```css
h2 {
    color: #2E8B57;
    text-align: center;
}

ul {
    background-color: lightyellow;
    padding: 10px;
}

li {
    list-style-type: none;
    padding: 5px;
    border: 1px solid gray;
    margin: 5px;
}

li:hover {
    cursor: pointer;
    background-color: #ffffe0;
}
```

---

## Exercice 04 - Tableau

```css
table {
    margin: 20px auto;
    border-collapse: collapse;
}

th, td {
    border: 1px solid black;
    padding: 10px;
    text-align: left;
}

th {
    background-color: lightblue;
}

tbody tr:hover {
    background-color: #f0f0f0;
}
```

---

## Exercice 05 - Images

```css
img {
    display: block;
    margin: 20px auto;
    max-width: 400px;
    height: auto;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
}

img:hover {
    transform: scale(1.05);
    transition: 0.3s;
}
```

---

## Exercice 06 - Formulaire

```css
label {
    display: block;
    margin-top: 10px;
    font-weight: bold;
}

input, select {
    width: 100%;
    padding: 8px;
    border: 2px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

input:focus {
    border-color: #4CAF50;
    outline: none;
}

button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 10px;
}

button:hover {
    background-color: #45a049;
}
```

---

## Exercice 07 - Classes

```css
.carte {
    background-color: white;
    padding: 20px;
    margin: 10px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.bloc-important {
    background-color: #ffe6e6;
    border-left: 5px solid red;
    padding: 10px;
}

.bloc-info {
    background-color: #e6f3ff;
    border-left: 5px solid blue;
    padding: 10px;
}

.texte-centre {
    text-align: center;
}
```

---

## Exercice 08 - Flexbox

```css
.conteneur {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    gap: 20px;
}

.item {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
    border-radius: 10px;
    width: 150px;
    text-align: center;
}

.item:hover {
    transform: translateY(-5px);
    transition: 0.3s;
}
```

---

## Exercice 09 - Animations

```css
@keyframes rebond {
    0% { transform: translateY(0); }
    50% { transform: translateY(-20px); }
    100% { transform: translateY(0); }
}

.creeper {
    animation: rebond 1s infinite;
}

@keyframes rotation {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
}

.diamant {
    animation: rotation 3s infinite linear;
}
```

---

## Exercice 10 - Projet Final

Il n'y a pas de solution unique pour le projet final ! C'est l'occasion pour Raphaël d'être créatif et d'utiliser toutes les techniques apprises. Voici un exemple de ce qu'on pourrait faire :

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background: linear-gradient(to bottom, #87CEEB, #98FB98);
}

header {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    text-align: center;
    padding: 40px 20px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.2);
}

nav {
    background-color: #333;
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 10px 20px;
    border-radius: 5px;
    transition: 0.3s;
}

nav a:hover {
    background-color: #4CAF50;
}

main {
    max-width: 1000px;
    margin: 30px auto;
    padding: 20px;
}

section {
    background-color: white;
    margin: 20px 0;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.outils-container {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    justify-content: space-around;
}

.outil {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
    border-radius: 10px;
    width: 200px;
    text-align: center;
    transition: 0.3s;
}

.outil:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 16px rgba(0,0,0,0.2);
}

table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
}

th, td {
    border: 1px solid #ddd;
    padding: 12px;
    text-align: left;
}

th {
    background-color: #4CAF50;
    color: white;
}

tbody tr:hover {
    background-color: #f5f5f5;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}
```

---

## 💡 Conseils pédagogiques

- Laissez Raphaël essayer d'abord
- Si bloqué > 5 minutes, donnez un petit indice
- Encouragez l'expérimentation (changer les couleurs, valeurs...)
- Célébrez chaque réussite !
- Le projet final peut prendre plusieurs sessions

Bon enseignement ! 🎓
