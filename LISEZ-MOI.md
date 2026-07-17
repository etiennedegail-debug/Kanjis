# Kanji — révision quotidienne · installation sur Android

88 kanji (leçons 21 à 31), 6 nouveaux par jour, plafond à 16 cartes.
Fonctionne **hors ligne** une fois installée. La progression est stockée sur ton téléphone.

## Pourquoi ce n'est pas un APK

Un vrai APK demande le SDK Android et une signature. Une PWA donne le même résultat
concret — icône sur l'écran d'accueil, plein écran, hors ligne — sans passer par le
Play Store ni par l'activation des « sources inconnues ».

## Installation (une fois, ~10 minutes)

Une PWA doit être servie en HTTPS pour s'installer. Le plus simple est GitHub Pages, gratuit.

1. Crée un compte sur github.com si tu n'en as pas.
2. Nouveau dépôt **public**, nommé par exemple `kanji`.
3. « Add file » → « Upload files » → dépose les 5 fichiers de ce dossier
   (`index.html`, `manifest.webmanifest`, `sw.js`, et les 3 `icon-*.png`). Commit.
4. Onglet **Settings** → **Pages** → Source : `Deploy from a branch`, branche `main`, dossier `/ (root)`. Save.
5. Attends ~1 minute. L'adresse apparaît : `https://TON-PSEUDO.github.io/kanji/`
6. Ouvre cette adresse **dans Chrome sur ton Android**.
7. Menu ⋮ → **Installer l'application** (ou « Ajouter à l'écran d'accueil »).

C'est fini. L'icône 漢 est sur ton écran d'accueil. Coupe le wifi pour vérifier : ça marche toujours.

## Si tu ne veux pas de GitHub

Ouvre `index.html` directement depuis les fichiers de ton téléphone. Ça fonctionne,
mais sans installation ni icône, et la progression est plus fragile (Chrome peut
purger le stockage des fichiers locaux). Je le déconseille pour un usage quotidien.

## Utilisation

- **Espace** ou le bouton bleu : révéler
- **1 / 2 / 3** : Raté / Difficile / Su
- **T** ou le bouton « Ordre des traits » : voir le tracé animé
- Le sceau 済 signifie que la journée est finie. Ferme l'appli.

## Deux cartes marquées ⚑

- **糸** : phrase d'exemple composée par Claude — ta fiche n'en donne aucune.
- **日** : lecture on à vérifier sur ta fiche p. 317, le scan était illisible.

## Crédits

Tracés : [KanjiVG](http://kanjivg.tagaini.net) (Ulrich Apel), licence CC BY-SA 3.0.
Contenu des fiches : Direct Japanese / Institut Japonais de Langues, à usage personnel.
