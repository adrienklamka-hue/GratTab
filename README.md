# 🎸 Grat'Tab — Dictionnaire d'accords de guitare

Application web complète, sans aucune dépendance externe, qui fonctionne hors-ligne et s'installe comme une vraie app sur téléphone.

## Fonctionnalités

- **Tous les accords** : 12 fondamentales × 17 types (majeur, mineur, 7, m7, maj7, sus2/4, 6, m6, 9, add9, dim, dim7, aug, m7♭5…)
- **Positions ouvertes et barrés** transposables (formes Mi, La, Ré), doigtés, notes réelles
- **Écoute** : synthèse de corde pincée dans le navigateur — 3 timbres (classique nylon, électro-acoustique, électrique), gratté, arpège, note par note
- **Capodastre** 0–9 avec pédagogie de transposition, et **Capo malin** qui transforme un accord difficile en forme ouverte
- **L'Oreille** : reconnaissance des accords au micro, en direct, avec historique
- **Mes morceaux** : chaque grille captée en Live peut être enregistrée avec le nom de la chanson, pour la recharger ou la jouer en Jam plus tard
- **Chord Hero (Jam noté)** : l'appli t'écoute jouer une grille et note ta précision — points, combos, record
- **Mode Live YouTube** : la vidéo joue dans l'appli et l'accord à jouer s'affiche en direct, en grand, avec son diagramme
- **Grille d'un morceau** : charge un fichier audio, l'appli extrait la grille d'accords synchronisée à la lecture (façon Chordify), avec meilleur capo et accords simplifiés
- Mode gaucher, notation Do Ré Mi ↔ C D E, recherche, favoris, progressions pédagogiques, **accordeur à aiguille** (micro) avec sons de référence

## Déploiement sur GitHub Pages

1. Crée un dépôt (par exemple `grattab`) sur GitHub.
2. Dépose **tous les fichiers de ce dossier** à la racine du dépôt :
   - `index.html` · `manifest.json` · `sw.js`
   - `icone-192.png` · `icone-512.png` · `apple-touch-icon.png`
3. Dans le dépôt : **Settings → Pages → Source : Deploy from a branch → Branch : main / (root) → Save**.
4. Après une minute, l'appli est en ligne sur `https://TON-PSEUDO.github.io/grattab/`.

## Installation sur iPhone

Ouvre l'URL dans **Safari** → bouton Partager → **« Sur l'écran d'accueil »**. L'appli s'ouvre alors en plein écran, avec son icône, et fonctionne hors-ligne.

## Installation sur Android

Ouvre l'URL dans **Chrome** → bannière **« Installer l'application »** (ou menu ⋮ → **« Ajouter à l'écran d'accueil »**) → **Installer**. L'appli apparaît sur l'écran d'accueil et dans le tiroir d'applications, se lance en plein écran et se met à jour toute seule. Au premier usage du micro, choisis « Pendant l'utilisation ».

## Mode Live YouTube (mobile)

Colle un lien YouTube → la vidéo s'ouvre dans l'appli → lance-la, son sur les haut-parleurs (pas d'écouteurs) → **Mode Live** : l'accord à jouer s'affiche en grand, en temps réel, avec son diagramme, et l'écran reste allumé pendant toute la session.

## Notes

- Le **micro** (l'Oreille) nécessite HTTPS — c'est le cas sur GitHub Pages — et ton autorisation au premier lancement.
- **YouTube / Deezer** : leurs flux sont protégés, une page web ne peut pas les lire directement. Fais jouer le morceau sur tes enceintes avec l'Oreille, ou charge un fichier audio que tu possèdes.
- Les **favoris** sont enregistrés localement dans ton navigateur.
