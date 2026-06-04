# 📄 CV HTML5 Pur — NAMBIMAN Eben-Ezer

> Projet réalisé dans le cadre du **Sprint 02** de formation en Programmation Web (méthode FORGE).  
> ✅ **Validé sans erreur sur le W3C Validator** — Document checking completed.

---

## 🎯 Objectif du projet

Créer un **CV en HTML5 sémantique pur**, sans aucune ligne de CSS ni de JavaScript.  
Chaque balise utilisée a un sens sémantique précis.

---

## 📁 Structure du projet

```
projet-cv/
├── index.html        → Le fichier principal du CV (validé W3C ✅)
├── profil-01.webp    → Photo de profil
└── README.md         → Ce fichier
```

---

## 🏗️ Structure HTML utilisée

| Zone HTML       | Rôle dans le CV                                        |
|-----------------|--------------------------------------------------------|
| `<header>`      | Nom, titre, photo de profil, contacts cliquables       |
| `<main>`        | Contenu principal du CV                                |
| `<aside>`       | Compétences, études, langues, hobbies                  |
| `<section>`     | À propos, expériences, formations, diplômes            |
| `<footer>`      | Liens vers les réseaux professionnels + copyright      |
| `<nav>`         | Navigation vers LinkedIn, GitHub, Email                |
| `<figure>`      | Photo de profil avec légende `<figcaption>`            |
| `<hr>`          | Séparation logique entre les grandes zones             |

---

## 🔖 Balises sémantiques clés

| Balise               | Usage dans le CV                        |
|----------------------|-----------------------------------------|
| `<strong>`           | Noms d'entreprises, titres de poste     |
| `<em>`               | Dates et périodes                       |
| `<ul>` / `<li>`      | Listes de compétences, diplômes         |
| `<a href="mailto:">` | Email cliquable                         |
| `<a href="tel:">`    | Téléphone cliquable (mobile)            |
| `<img alt="">`       | Photo avec texte alternatif             |
| `<figcaption>`       | Légende de la photo de profil           |
| `&amp;`              | Caractère & correctement échappé        |
| `&copy;`             | Symbole © en entité HTML                |

---

## ♿ Accessibilité

- Attribut `alt` renseigné sur toutes les images
- Attribut `aria-label` sur la balise `<nav>` du footer
- Structure de titres hiérarchique (`<h1>` → `<h2>`)
- Liens explicites et descriptifs (LinkedIn, GitHub, Email)
- Numéro de téléphone cliquable via `href="tel:"`
- Email cliquable via `href="mailto:"`

---

## 🌐 Liens professionnels

| Réseau   | Lien                                          |
|----------|-----------------------------------------------|
| LinkedIn | https://linkedin.com/in/eben-ezernambiman      |
| GitHub   | https://github.com/ebenezer-n                 |
| Email    | ebenezernambiman9@gmail.com                   |

---

## ✅ Validation W3C

Fichier testé et validé sur :  
🔗 https://validator.w3.org/nu/#textarea

> *"Document checking completed. No errors or warnings to show."*

---

## 👤 Auteur

**NAMBIMAN Eben-Ezer**  
Développeur Web & Mobile Junior  
📧 ebenezernambiman9@gmail.com  
📞 +229 01 90 92 18 66

---

*Projet Sprint 02 — Formation IMeN BENIN — 2026*
