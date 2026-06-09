# 📄 CV HTML5 — NAMBIMAN Eben-Ezer

> CV personnel statique développé en HTML5 sémantique pur, stylisé avec un thème **Tech Sombre** via CSS3.

---

## 🗂️ Structure des fichiers

```
cv/
├── index.html       # Structure sémantique du CV
├── style.css        # Feuille de styles (thème dark tech)
└── ma-photo.jpg     # Photo de profil (à fournir)
```

---

## 🧱 Architecture HTML

Le document suit une structure sémantique HTML5 en trois zones :

| Balise | Rôle |
|---|---|
| `<header>` | Photo de profil, nom, titre et contacts |
| `<main>` | Corps du CV en deux colonnes (`<aside>` + `<section>`) |
| `<aside>` | Colonne gauche : Compétences, Études, Langues, Hobbies |
| `<section>` | Colonne droite : Expériences, Formations, Diplômes, À propos |
| `<footer>` | Liens utiles (LinkedIn…) |

---

## 🎨 Charte graphique (style.css)

Thème inspiré des éditeurs de code — sobre, lisible, professionnel.

| Rôle | Couleur | Hex |
|---|---|---|
| Fond principal (60%) | Bleu-nuit | `#0F172A` |
| Texte principal (30%) | Gris clair | `#E2E8F0` |
| Accent principal (10%) | Vert émeraude | `#10B981` |
| Accent secondaire | Bleu électrique | `#3B82F6` |
| Texte secondaire | Gris doux | `#94A3B8` |

**Typographies (Google Fonts) :**
- `Space Grotesk` — titres (h1, h2, h3)
- `Inter` — corps de texte

---

## ⚙️ Règles CSS clés

- **Box model unifié** : `box-sizing: border-box` appliqué globalement via `*`
- **Photo de profil** : circulaire (`border-radius: 50%`), centrée, bordure verte émeraude
- **Badges `<li>`** : fond `#1E293B`, bordure bleue, coins arrondis
- **Titres `h2`** : barre décorative verte à gauche (`border-left: 4px solid #10B981`)
- **Liens `<a>`** : bleu électrique, soulignement au survol uniquement

---

## 🚀 Lancement

Aucune dépendance, aucun build requis. Ouvrir directement dans un navigateur :

```bash
# Option 1 — double-clic sur le fichier
open index.html

# Option 2 — serveur local (VS Code Live Server ou Python)
python -m http.server 8000
```

Puis naviguer vers `http://localhost:8000`.

---

## ⚠️ Prérequis

- Placer une image nommée **`ma-photo.jpg`** à la racine du projet pour afficher la photo de profil.
- Connexion internet requise au premier chargement pour les polices Google Fonts.

---

## ✍️ Auteur

**NAMBIMAN Eben-Ezer** — Développeur Web & Mobile Junior  
📧 ebenezernambiman@gmail.com | 📞 +229 01 90 92 18 66  
🔗 [LinkedIn](https://linkedin.com/in/eben-ezer-nambiman)

---

*#EbenEzerTech — CONSTRUIRE DES SOLUTIONS, PAS JUSTE DU CODE.*
