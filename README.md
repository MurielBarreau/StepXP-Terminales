# StepXP — Savoir S'entraîner Physiquement (Terminales)

Application web (PWA) pour les élèves de terminale : zones de fréquence cardiaque (Karvonen), orbes, modes **Chill / Combo / Turbo**, chrono des séries, carnet d'entraînement, projet de transformation, XP et talents.

- Fonctionne hors connexion une fois installée (service worker).
- Aucune donnée collectée : tout reste sur l'appareil de l'élève (stockage local, préfixe `stepxpt`).

## Les 3 modes de série

| Mode | Zone | Nature de l'effort | Exemple de série |
|---|---|---|---|
| CHILL | Zone 2 | Modéré et prolongé | 2×18' R=4' |
| COMBO | Zone 3 | Long et soutenu | 4×6' R=3' |
| TURBO | Zones 4 / 5 | Bref et intense | 3×(8×30''/30'') R=4' |

## Mise en ligne sur GitHub Pages

1. Déposer **tous** les fichiers de ce dossier à la racine d'un dépôt (ou d'un sous-dossier dédié).
2. *Settings → Pages → Deploy from a branch → main / (root)*.
3. L'application est ensuite disponible à `https://<compte>.github.io/<depot>/`.

Tous les chemins sont relatifs et le cache hors ligne porte le nom `stepxpt-…` : l'appli ne gêne pas les autres applis hébergées sur le même compte.
Pour publier une mise à jour, changer `CACHE = "stepxpt-v1"` en `"stepxpt-v2"` dans `sw.js`.

## Licence

© Muriel Barreau, CEDREPS, 2026 — [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.fr) : réutilisation libre avec attribution, sans usage commercial.
