# Character Finder — Détection de personnages fictifs par vision par ordinateur

Projet réalisé dans le cadre du cours d'Informatique Graphique et Vision — Licence Informatique (L3), Université Lyon 2.  
Application de détection de personnages fictifs dans une collection d'images, utilisant l'algorithme SIFT et le matching de descripteurs.

---

## Concept

L'utilisateur choisit une **imagette** (petite image de référence d'un personnage) et un **dossier d'images** à analyser. L'application compare automatiquement l'imagette à chaque image du dossier et indique si le personnage est détecté ou non.

---

## Technologies utilisées

- **Python** — langage principal
- **OpenCV** — traitement d'image et vision par ordinateur
- **Jupyter Notebook** — environnement de développement

---

## Algorithmes utilisés

- **SIFT** (Scale-Invariant Feature Transform) — détection des points clés et calcul des descripteurs dans chaque image
- **Brute Force Matcher (BFMatcher)** — mise en correspondance des descripteurs entre l'imagette et les images cibles
- **Test de ratio de Lowe** — filtrage des correspondances pour ne garder que les matches fiables (seuil à 0.8)

---

## Fonctionnalités

- Détection parmi 10 personnages fictifs issus de jeux vidéo et d'animes
- Affichage de l'imagette et des points clés SIFT détectés
- Affichage du nombre de matches valides pour chaque image analysée
- Possibilité de relancer l'application après chaque analyse

---

## Personnages disponibles

| Jeux vidéo | Animes / Animation |
|:-:|:-:|
| Aloy *(Horizon)* | Kurumi Tokisaki *(Date A Live)* |
| Sage *(Valorant)* | Lelouch Vi Britannia *(Code Geass)* |
| Sonic | Loona *(Helluva Boss)* |
| Pikachu *(Pokémon)* | Maomao *(La Pharmacienne)* |
| | March 7th *(Honkai: Star Rail)* |
| | Violet Evergarden |

---

## Installation

```bash
pip install opencv-python jupyter
```

Puis lancer le notebook :

```bash
jupyter notebook
```

---

## Auteures

- **Serena Pot** — [@Aid4n4](https://github.com/Aid4n4)
- **Maély Thomas** — [@Nekokimi0](https://github.com/Nekokimi0)
- Université Lyon 2, janvier 2026
