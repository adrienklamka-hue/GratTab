# 🎸 Luthier — Dictionnaire d'accords de guitare

Application web complète, sans aucune dépendance externe, qui fonctionne hors-ligne et s'installe comme une vraie app sur téléphone.

## Fonctionnalités

- **Tous les accords** : 12 fondamentales × 17 types (majeur, mineur, 7, m7, maj7, sus2/4, 6, m6, 9, add9, dim, dim7, aug, m7♭5…)
- **Positions ouvertes et barrés** transposables (formes Mi, La, Ré), doigtés, notes réelles
- **Écoute** : synthèse de corde pincée dans le navigateur — 3 timbres (classique nylon, électro-acoustique, électrique), gratté, arpège, note par note
- **Capodastre** 0–9 avec pédagogie de transposition, et **Capo malin** qui transforme un accord difficile en forme ouverte
- **L'Oreille** : reconnaissance des accords au micro, en direct, avec historique
- **Grille d'un morceau** : charge un fichier audio, l'appli extrait la grille d'accords synchronisée à la lecture (façon Chordify), avec meilleur capo et accords simplifiés
- Mode gaucher, notation Do Ré Mi ↔ C D E, recherche, favoris, progressions pédagogiques, accordeur

## Déploiement sur GitHub Pages

1. Crée un dépôt (par exemple `luthier`) sur GitHub.
2. Dépose **tous les fichiers de ce dossier** à la racine du dépôt :
   - `index.html` · `manifest.json` · `sw.js`
   - `icone-192.png` · `icone-512.png` · `apple-touch-icon.png`
3. Dans le dépôt : **Settings → Pages → Source : Deploy from a branch → Branch : main / (root) → Save**.
4. Après une minute, l'appli est en ligne sur `https://TON-PSEUDO.github.io/luthier/`.

## Installation sur iPhone

Ouvre l'URL dans **Safari** → bouton Partager → **« Sur l'écran d'accueil »**. L'appli s'ouvre alors en plein écran, avec son icône, et fonctionne hors-ligne.

## Notes

- Le **micro** (l'Oreille) nécessite HTTPS — c'est le cas sur GitHub Pages — et ton autorisation au premier lancement.
- **YouTube / Deezer** : leurs flux sont protégés, une page web ne peut pas les lire directement. Fais jouer le morceau sur tes enceintes avec l'Oreille, ou charge un fichier audio que tu possèdes.
- Les **favoris** sont enregistrés localement dans ton navigateur.
