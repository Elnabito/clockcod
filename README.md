# Clockcod – WOD Timer

Timer de WOD façon afficheur LED de box : **Horloge, For Time, AMRAP, EMOM, Tabata**,
plus un mode **Pomodoro** à l'interface douce (anneau de progression, carillons légers,
pause longue après chaque série de 4, bouton « Passer »).
Application web installable (PWA) qui fonctionne hors ligne.

Site : https://elnabito.github.io/clockcod/

## Installer sur Android

1. Ouvrir l'adresse ci-dessus dans **Chrome**.
2. Menu ⋮ → **Ajouter à l'écran d'accueil** (ou « Installer l'application »).
3. Lancer Clockcod depuis l'icône : plein écran, sans barre d'adresse, utilisable hors ligne.

## Utilisation

- Choisir un mode en haut, régler les paramètres, puis **START**.
- AMRAP / For Time : toucher l'afficheur pour compter un round (**−1 RND** pour corriger).
- 🔊 coupe ou remet les bips, ⛶ passe en plein écran paysage.
- L'écran reste allumé pendant le décompte (Wake Lock).

## Fichiers

- `index.html` : toute l'appli (HTML, CSS, JS).
- `manifest.webmanifest` : nom, icônes, couleurs pour l'installation.
- `sw.js` : service worker (cache hors ligne). Changer `VERSION` à chaque mise à jour.
- `icons/` : icônes 192 et 512 px (dont une « maskable » pour Android).
