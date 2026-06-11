# FONTE — version application autonome (PWA)

Même app que sur Claude, mais avec **son propre logo**, en **plein écran** (aucune interface Claude autour) et qui **marche hors connexion** une fois installée.

## Mettre l'app en ligne (gratuit, ~5 min)

### Option A — GitHub Pages (recommandé)
1. Va sur **github.com** (crée un compte gratuit si besoin).
2. **New repository** → nom : `fonte` → Public → **Create repository**.
3. Clique **« uploading an existing file »** → glisse **tous les fichiers de ce dossier** (pas le dossier lui-même : index.html, app.js, sw.js, manifest.webmanifest et les images) → **Commit changes**.
4. **Settings → Pages** → Branch : `main` → **Save**.
5. Attends 1-2 minutes. Ton app est sur : `https://TON-PSEUDO.github.io/fonte/`

### Option B — Netlify Drop
1. Va sur **app.netlify.com/drop** (compte gratuit).
2. Glisse le dossier entier → tu obtiens une URL direct.

## Installer sur ton téléphone
- **iPhone (Safari)** : ouvre l'URL → bouton Partager → **« Sur l'écran d'accueil »** → l'icône haltère FONTE apparaît, l'app s'ouvre en plein écran.
- **Android (Chrome)** : ouvre l'URL → menu ⋮ → **« Installer l'application »**.

## Récupérer tes données existantes
1. Dans la version Claude de FONTE : **Réglages → Exporter mes données** (un fichier .json est téléchargé, photos comprises).
2. Dans la nouvelle app : **Réglages → Importer des données** → choisis ce fichier.

## Mettre à jour l'app plus tard
Quand Claude te donne une nouvelle version : remplace `app.js` (et les autres fichiers modifiés) dans ton repo GitHub → Commit. Tes données ne bougent pas (elles sont stockées sur ton téléphone, pas dans les fichiers).
