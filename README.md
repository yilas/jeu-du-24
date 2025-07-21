# 🎯 Jeu du 24

Ce projet est une petite webapp interactive développée en HTML, CSS et JavaScript, permettant de jouer au célèbre **jeu du 24**.

## 🕹️ Règle du jeu

Vous devez **trouver une expression mathématique qui donne 24** en utilisant les **quatre chiffres** proposés, chacun **exactement une fois**.
Les opérations autorisées sont : `+`, `-`, `×`, et `÷`.

Exemple :
Pour les chiffres `4, 1, 8, 7` une solution est :
`((7 - 1) × (8 - 4)) = 24`

## 🚀 Fonctionnalités

- Interface responsive (adaptée aux mobiles et aux écrans larges)
- Saisie rapide avec passage automatique au champ suivant
- Clavier numérique sur mobile
- Animation visuelle en cas de succès ou d'échec
- Bouton de réinitialisation
- Mode sombre / clair automatique
- Sélecteur de thème manuel (dark / light)
- Favicon personnalisé
- Animation d’intro
- **Déploiement facile via GitHub Pages**

## 📦 Installation

Clonez ce dépôt :

```bash
git clone https://github.com/yilas/jeu-du-24.git
cd jeu-du-24
```

Ouvrez index.html dans un navigateur.

## 🌐 Déploiement sur GitHub Pages

1. Activez GitHub Pages dans les paramètres du dépôt (branche main, dossier racine).
1. Accédez à votre site à l’adresse : `https://<votre-utilisateur>.github.io/jeu-du-24/`

## 🧱 Structure du projet

```bash
jeu-du-24/
├── index.html        # Page principale du jeu
├── style.css         # Styles et animations
├── script.js         # Logique du jeu
├── favicon.png       # Icône du site
└── README.md         # Documentation
```

© 2025 – Yann Ilas
