# 📄 CV Professionnel HTML5 & CSS3

## 📌 Présentation

Ce projet consiste en la réalisation d'un **Curriculum Vitae numérique** développé en **HTML5 sémantique** et **CSS3 pur**, dans le cadre de la formation **Développement Web & Mobile** à IMeN BENIN.

L'objectif pédagogique est de maîtriser :

- La structuration sémantique d'une page web.
- Le modèle de boîte CSS (Box Model).
- Les comportements des éléments Block et Inline.
- La mise en page sans Flexbox ni Grid.
- L'application d'une charte graphique cohérente.
- Les bonnes pratiques d'accessibilité et de lisibilité.

---

## 🎯 Objectifs du Projet

Ce CV a été conçu afin de :

- Présenter le parcours académique et professionnel de l'auteur.
- Mettre en pratique les notions fondamentales du HTML5 et du CSS3.
- Produire une interface responsive simple basée sur le flux naturel du document.
- Comprendre les mécanismes de mise en page traditionnels avant l'utilisation de technologies modernes comme Flexbox ou CSS Grid.

---

## 👨‍💻 Auteur

**NAMBIMAN Eben-Ezer**

Développeur Web & Mobile Junior

📧 ebenezernambiman9@gmail.com

📞 +229 01 90 92 18 66

🔗 LinkedIn : https://linkedin.com/in/eben-ezernambiman

🔗 GitHub : https://github.com/ebenezer-n

---

## 🏗 Structure du Projet

```text
cv-html-css/
│
├── index.html
├── style.css
├── profil-01.webp
└── README.md
```

---

## 📚 Technologies Utilisées

| Technologie | Rôle |
|------------|------|
| HTML5 | Structure sémantique du document |
| CSS3 | Mise en forme et mise en page |
| Google Fonts | Typographie du projet |
| Git | Gestion des versions |
| GitHub | Hébergement du code |

---

## 🧱 Structure HTML

Le document utilise les balises sémantiques suivantes :

```html
<header>
<main>
<section>
<footer>
```

Organisation générale :

- En-tête du CV
- Présentation personnelle
- Compétences
- Expériences professionnelles
- Formations
- Diplômes
- Études
- Langues
- Hobbies
- Pied de page

---

## 🎨 Charte Graphique

Le projet applique la règle de design **60-30-10** :

| Couleur | Utilisation |
|----------|------------|
| #0F172A | Fond principal |
| #E2E8F0 | Texte principal |
| #10B981 | Accent principal |
| #3B82F6 | Accent secondaire |

Inspirée des interfaces modernes de développement et des éditeurs de code.

---

## 🔤 Typographies

### Titres

- Space Grotesk

### Texte courant

- Inter

Chargées depuis Google Fonts.

---

## 📦 Concepts CSS Mis en Pratique

### 1. Box Model

```css
* {
    box-sizing: border-box;
}
```

Permet de contrôler précisément les dimensions des éléments.

---

### 2. Centrage du Contenu

```css
.cv-container {
    max-width: 720px;
    margin: 0 auto;
}
```

Le CV est centré horizontalement grâce à `margin: auto`.

---

### 3. Mise en Page sans Flexbox

Les colonnes du header utilisent :

```css
display: inline-block;
```

pour positionner :

- la photo
- les informations personnelles

sur une même ligne.

---

### 4. Badges de Compétences

Les compétences sont affichées sous forme de badges :

```css
.liste-competences li {
    display: inline-block;
}
```

---

### 5. Boutons de Contact

Les liens sont transformés en boutons grâce à :

```css
display: inline-block;
```

et un système de survol :

```css
:hover
```

---

## 📱 Responsive Design

Le projet reste lisible sur les petits écrans grâce à :

```css
width: 100%;
max-width: 720px;
```

Le contenu s'adapte naturellement à la largeur disponible.

---

## 📖 Contenu du CV

### Compétences

- HTML5
- CSS3
- JavaScript
- PHP
- MySQL
- Git
- Maintenance Informatique
- Analyse Financière

### Expériences

- Développeur Web & Mobile Junior
- Secrétaire Administratif
- Électricien

### Formations

- AGS
- IREDE GROUP
- IMeN BENIN

### Langues

- Français (Courant)
- Anglais (Intermédiaire)

### Centres d'intérêt

- Lecture
- Blog informatique
- Musique

---

## 🚀 Lancer le Projet

1. Télécharger le dépôt GitHub.

```bash
git clone <url-du-depot>
```

2. Ouvrir le dossier.

```bash
cd cv-html-css
```

3. Ouvrir le fichier :

```text
index.html
```

dans un navigateur web.

---

## 🎓 Contexte Pédagogique

Projet réalisé dans le cadre de la formation :

**Développement Web & Mobile**
IMeN BENIN

Sprint 03 - Méthode FORGE

Compétences travaillées :

- HTML5 Sémantique
- CSS3 Fondamental
- Box Model
- Display Block / Inline
- Mise en page traditionnelle
- Accessibilité
- Structuration de contenu

---

## 📜 Licence

Projet réalisé à des fins pédagogiques et de démonstration.

© 2026 NAMBIMAN Eben-Ezer - IMeN BENIN
