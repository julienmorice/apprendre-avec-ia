# Apprendre avec l'IA — Atelier de rentrée PracTice

Présentation du bloc IA de l'atelier de rentrée des nouveaux entrants
d'IMT Business School, le 31 août 2026.

**En ligne : https://julienmorice.github.io/apprendre-avec-ia/**

Julien Morice — Service PracTice, IMT Business School.

## Déroulé

1. **`index.html`** (racine du site) — page d'ouverture « La Gen Z à l'ère
   de l'IA », avec la vidéo de mise en contexte et un bouton pour enchaîner
   vers la présentation.
2. **`presentation.html`** — la présentation elle-même, 21 slides.

## Utilisation

Page HTML autonome, 21 slides, scène 16:9 mise à l'échelle.

| Touche | Action |
|---|---|
| `→` `espace` `Entrée` | slide suivante |
| `←` `retour arrière` | slide précédente |
| `F` | plein écran |
| `S` | sommaire cliquable (ou clic sur le numéro de slide) |
| `Échap` | fermer le sommaire |
| `Début` / `Fin` | première / dernière slide |

L'adresse retient la position (`#12`), ce qui permet de reprendre où on
en était après un rechargement.

### Sur téléphone et tablette

Sans souris il n'y a pas de survol, et sans clavier pas de raccourci : les
commandes sont donc affichées en permanence sur les appareils tactiles.

- **Glisser** vers la gauche ou la droite pour changer de slide.
- Les **flèches** ‹ › sont visibles en bas (portrait) ou sur les côtés (paysage).
- Le **bouton grille** en bas à gauche ouvre le sommaire.
- Au-dessus d'un lecteur vidéo, le glissement appartient au lecteur : utiliser
  les flèches.

En portrait, la scène 16:9 se réduit à une bande étroite et le texte devient
petit ; un indice invite à tourner l'appareil. **La présentation se lit en
paysage.**

## Vidéos

Les cinq démonstrations sont des lecteurs MediaServer IP Paris (UbiCast)
intégrés en `iframe`. Chaque slide vidéo porte aussi un lien « Ouvrir la
vidéo dans un onglet », utile si le lecteur ne se charge pas.

## Structure

```
index.html         page d'ouverture « La Gen Z à l'ère de l'IA » (vidéo) — racine du site
presentation.html   toute la présentation, styles et scripts compris
images/             visuels des slides et QR codes
```

Le QR code « toute la présentation en ligne » de la dernière slide pointe
directement vers `presentation.html`, sans repasser par la vidéo
d'ouverture pour qui le scanne après coup.
