# Mise en ligne du podcast — instructions

## 1. Créer le dépôt
Sur GitHub (compte `rbrdingenierie-ui`), créez un nouveau dépôt public nommé **exactement** :
`arcade_CESBF_act3_S2_podcast`
(ce nom doit correspondre à l'URL déjà utilisée dans le QR code du cours et du PowerPoint).

## 2. Déposer les fichiers
Dans ce dépôt, à la racine :
- `index.html` (fourni)
- un dossier `audio/` contenant vos 11 fichiers, nommés **exactement** :
  `M1a.mp3`, `M1b.mp3`, `M2a.mp3`, `M2b.mp3`, `M2c.mp3`, `M3a.mp3`, `M3b.mp3`,
  `M4a.mp3`, `M4b.mp3`, `M5a.mp3`, `M5b.mp3`

Le code de chaque épisode (M1a, M1b…) est repris du fichier de textes déjà fourni — chaque
lecteur audio de la page cherche le fichier correspondant dans `audio/`.

## 3. Activer GitHub Pages
Dans le dépôt : **Settings → Pages → Source : Deploy from a branch → Branch : main / (root) → Save**.
GitHub indique alors l'URL de publication (quelques minutes de délai la première fois) :
`https://rbrdingenierie-ui.github.io/arcade_CESBF_act3_S2_podcast/`

## 4. Vérifier
Une fois en ligne, testez chaque lecteur audio sur la page. Un épisode qui n'affiche que
« 0:00 / 0:00 » signifie que le fichier correspondant n'a pas encore été déposé, ou que le nom
ne correspond pas exactement (sensible à la casse).

Vous pouvez ajouter les épisodes progressivement : la page fonctionne même si certains fichiers
audio manquent encore (le lecteur reste juste vide pour ceux-là).
