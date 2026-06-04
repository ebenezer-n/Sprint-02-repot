📄 CV HTML5 Pur — NAMBIMAN Eben-Ezer
Projet réalisé dans le cadre du Sprint 02 de formation en Programmation Web (méthode FORGE).
✅ Validé sans erreur sur le W3C Validator — Document checking completed.


🎯 Objectif du projet
Créer un CV en HTML5 sémantique pur, sans aucune ligne de CSS ni de JavaScript.
L'objectif est de démontrer la maîtrise de la structure et de la sémantique HTML5 : chaque balise doit avoir un sens, pas juste un rôle visuel.


📁 Structure du projet
projet-cv/

├── index.html        → Le fichier principal du CV (validé W3C ✅)

├── profil-01.webp    → Photo de profil

└── README.md         → Ce fichier


🏗️ Structure HTML utilisée
Zone HTML
Rôle dans le CV
<header>
Nom, titre, photo de profil, contacts cliquables
<main>
Contenu principal du CV
<aside>
Compétences, études, langues, hobbies (colonne gauche)
<section>
À propos, expériences, formations, diplômes
<footer>
Liens vers les réseaux professionnels + copyright
<nav>
Navigation vers LinkedIn, GitHub, Email
<figure>
Photo de profil avec légende <figcaption>
<hr>
Séparation logique entre les grandes zones



🔖 Balises sémantiques clés
Balise
Usage dans le CV
<strong>
Noms d'entreprises, titres de poste
<em>
Dates et périodes
<ul> / <li>
Listes de compétences, diplômes, formations
<a href="mailto:">
Email cliquable
<a href="tel:">
Téléphone cliquable (mobile)
<img alt="">
Photo avec texte alternatif
<figcaption>
Légende de la photo de profil
&amp;
Caractère & correctement échappé
&copy;
Symbole © en entité HTML



🐛 Erreurs corrigées (W3C Validator)
Erreur 1 — Stray end tag <section> (ligne 118)
La balise </section> apparaissait une seconde fois alors que la section était déjà fermée.
Le bloc "À propos de moi" se trouvait hors de toute balise parente valide.

Correction : déplacement du bloc à l'intérieur de <section>, avant sa fermeture.
Erreur 2 — Stray end tag <main> (ligne 121)
Conséquence de l'erreur 1 : un second </main> orphelin apparaissait après le vrai </main>.

Correction : suppression du </main> en double.


♿ Accessibilité
Attribut alt renseigné sur toutes les images
Attribut aria-label sur la balise <nav> du footer
Structure de titres hiérarchique (<h1> → <h2>)
Liens explicites et descriptifs (LinkedIn, GitHub, Email)
Numéro de téléphone cliquable via href="tel:"
Email cliquable via href="mailto:"


🌐 Liens professionnels
Réseau
Lien
LinkedIn
https://linkedin.com/in/eben-ezernambiman
GitHub
https://github.com/ebenezer-n
Email
ebenezernambiman9@gmail.com



✅ Validation W3C
Fichier testé et validé sur :
🔗 https://validator.w3.org/nu/#textarea

"Document checking completed. No errors or warnings to show."


👤 Auteur
NAMBIMAN Eben-Ezer
Développeur Web & Mobile Junior
📧 ebenezernambiman9@gmail.com
📞 +229 01 90 92 18 66



Projet Sprint 02 — Formation IMeN BENIN — 2026

