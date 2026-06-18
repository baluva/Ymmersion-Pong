# 🏓 Pong en Java (Swing)

Un jeu de **Pong à deux joueurs** développé en **Java** avec une interface
graphique **Swing**, agrémenté d'un système de bonus/malus et de balles multiples.

## ✨ Fonctionnalités

- Deux joueurs en local sur le même clavier
- Système de **bonus** apparaissant toutes les 7 secondes :
  - 🟢 **Vitesse** — accélère les balles
  - 🔵 **Ralenti** — ralentit les balles
  - 🟣 **Multiplication** — duplique les balles à l'écran
- Accélération des balles à chaque rebond sur une raquette
- **Fin de partie** au premier joueur à atteindre 10 points

## 🎮 Commandes

| Joueur | Monter | Descendre |
|--------|--------|-----------|
| Joueur 1 (gauche) | `W` | `S` |
| Joueur 2 (droite) | `↑` | `↓` |

## 🚀 Compiler et lancer

Prérequis : un **JDK** (Java 17+ recommandé).

```bash
# Compiler
javac PongGame.java

# Lancer (les images de bonus doivent être dans le dossier courant)
java PongGame
```

> Les fichiers `la-vitesse.png`, `lent.png` et `fleches-multiples.png` (icônes des
> bonus) doivent rester à côté du `.class` pour s'afficher correctement.

## 📁 Contenu

```
.
├── PongGame.java        # Code du jeu (classes PongGame + Ball)
├── la-vitesse.png       # Icône bonus vitesse
├── lent.png             # Icône bonus ralenti
├── fleches-multiples.png# Icône bonus multiplication
├── index.html / style.css  # Mini page web de présentation / téléchargement
└── README.md
```

## 👨‍💻 Auteur

Louey Barbirou — Ynov.
