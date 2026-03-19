# 📚 Jeu de piste — Bibliothèque du 27 Septembre

Activité numérique de médiation : l'usager découvre le système de classement de la bibliothèque en cherchant 4 livres dans les rayons via le catalogue en ligne, et valide chaque trouvaille en scannant un QR code sur l'étagère.

---

## Contenu du dossier

| Fichier | Rôle |
|---|---|
| `index.html` | Le jeu de piste (page principale) |
| `validation-livre.html` | Page affichée après scan du QR code (couverture + bravo + explication cote) |
| `qrcodes-a-imprimer.png` | Planche A4 à imprimer et découper (QR codes 3×3 cm) |

---

## Publier sur GitHub Pages (étape par étape)

### 1. Crée un compte GitHub
👉 Va sur [github.com](https://github.com) et crée un compte gratuit si tu n'en as pas.  
Note bien ton **nom d'utilisateur** (ex : `greg-biblio`).

### 2. Crée un nouveau dépôt
- Clique sur le bouton vert **"New"** (ou **"Nouveau"**)
- Nom du dépôt : `bibli27sept`
- Coche **"Public"**
- Clique **"Create repository"**

### 3. Uploade les fichiers
- Dans ton nouveau dépôt, clique **"uploading an existing file"**
- Glisse-dépose les 3 fichiers :
  - `index.html`
  - `validation-livre.html`
  - `qrcodes-a-imprimer.png`
- Clique **"Commit changes"**

### 4. Active GitHub Pages
- Va dans **Settings** (onglet en haut du dépôt)
- Dans le menu gauche, clique **"Pages"**
- Sous *"Branch"*, sélectionne **`main`** puis **`/ (root)`**
- Clique **"Save"**

### 5. Attends 1-2 minutes ☕
GitHub Pages génère ton site. L'URL sera :
```
https://TON-USERNAME.github.io/bibli27sept/
```

---

## Mettre à jour les QR codes avec ta vraie URL

Une fois ton site en ligne, il faut **régénérer les QR codes** avec ta vraie URL.  
Reviens dans Claude et dis :

> "Mon nom d'utilisateur GitHub est **[ton-username]**, régénère les QR codes."

Je mettrai à jour la planche d'impression en 2 minutes.

---

## Imprimer et coller les QR codes

1. Imprime `qrcodes-a-imprimer.png` en **taille réelle** (ne pas "adapter à la page")
2. Découpe le long des traits gris
3. Colle chaque étiquette sur le **bord de l'étagère**, face au livre correspondant

| Couleur | Rayon |
|---|---|
| 🔴 Rouge | Bandes Dessinées |
| 🔵 Bleu foncé | Romans |
| 🟢 Vert | Jeunesse |
| 🟡 Or | ONE |
| 🟣 Violet | Arts du Spectacle |

---

## Modifier les livres ou les textes

Tous les contenus (titres, cotes, explications, anecdotes) se trouvent dans la variable `LIVRES` au début du `<script>` dans `index.html` et `validation-livre.html`.  
Les deux fichiers doivent toujours être **synchronisés**.

---

*Activité développée dans le cadre de la médiation numérique — Bibliothèque du 27 Septembre, Fédération Wallonie-Bruxelles.*
