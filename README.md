# 🎓 ECAM-EPMI Digital Showcase (epmi-info)

<p align="center">
  <a href="#-à-propos">À Propos</a> •
  <a href="#-fonctionnalités">Fonctionnalités</a> •
  <a href="#-architecture-du-projet">Architecture</a> •
  <a href="#-aperçu-technique">Techno</a> •
  <a href="#-installation-locale">Installation</a>
</p>

<p align="center">
  <img src="https://shields.io" alt="Version"/>
  <img src="https://shields.io" alt="HTML5"/>
  <img src="https://shields.io" alt="CSS3"/>
  <img src="https://shields.io" alt="UI/UX"/>
</p>

---

## 📖 À propos

**epmi-info** est une passerelle numérique interactive conçue pour explorer et cartographier l'écosystème pédagogique de l'école d'ingénieurs **ECAM-EPMI**. 

Ce site web vitrine met en lumière de manière moderne et structurée les différentes **disciplines académiques**, les **activités étudiantes** et les **parcours d'innovation** proposés au sein de l'établissement. Développé en Front-End pur (*Vanilla Web*), ce projet met l'accent sur la clarté de l'information et une expérience utilisateur fluide.

## ✨ Fonctionnalités

- 🧭 **Navigation Intuitive :** Menu sémantique permettant de basculer facilement entre la présentation générale et le détail des disciplines.
- 📐 **Architecture Propre :** Séparation stricte des responsabilités (Fichiers HTML pour la structure, feuilles CSS pour le design, assets groupés).
- 📱 **Responsive Design :** Interface pensée pour offrir une lecture confortable aussi bien sur ordinateur que sur smartphone.
- 🎨 **Esthétique Soignée :** Charte graphique adaptée à l'identité visuelle et au dynamisme de l'univers étudiant de l'école.

## 🗂️ Architecture du Projet

Le dépôt est organisé de façon modulaire pour faciliter sa maintenance et ses futures évolutions :

```text
epmi-info/
├── css/
│   └── style.css          # Centralisation des styles graphiques et du layout
├── html/
│   └── disciplines.html   # Pages secondaires dédiées aux parcours d'études
├── images/
│   └── [...]              # Galerie d'illustrations, logos et photos du campus
├── index.html             # Point d'entrée principal du site (Page d'accueil)
└── README.md              # Documentation du projet
```

## 🛠️ Aperçu Technique

- **Sémantique HTML5 :** Utilisation des balises modernes (`<header>`, `<nav>`, `<section>`, `<footer>`) pour un meilleur référencement et une accessibilité optimisée.
- **Flexbox & Grid CSS :** Alignements et grilles modernes pour garantir la fluidité de la mise en page sans framework lourd.
- **Zéro dépendance :** Chargement instantané des pages grâce à l'absence de scripts ou de bibliothèques tierces superflues.

## 🚀 Installation Locale

Pour explorer ou modifier le projet sur votre machine, aucune configuration complexe n'est requise :

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com
   ```
2. **Accéder au dossier :**
   ```bash
   cd epmi-info
   ```
3. **Lancer le site :**
   Double-cliquez simplement sur le fichier `index.html` pour l'ouvrir dans votre navigateur favori, ou utilisez l'extension *Live Server* sur VS Code pour un rechargement automatique en temps réel.

---
<p align="center">Fait avec 💻 pour valoriser l'ingénierie et l'innovation à l'ECAM-EPMI.</p>
