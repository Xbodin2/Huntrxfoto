# 🎭 HuntrX AR — K-Pop Demon Hunters

Application de réalité augmentée pour les toppers de gâteau HuntrX.  
Compatible **iOS · Android · Web** — Aucune installation requise.

---

## 🚀 Déploiement sur GitHub Pages

### Étape 1 — Créer le dépôt GitHub

1. Connectez-vous sur [github.com](https://github.com)
2. Cliquez **"New repository"**
3. Nommez-le : `huntrx-ar` (ou ce que vous souhaitez)
4. Sélectionnez **Public**
5. Cliquez **"Create repository"**

---

### Étape 2 — Uploader les fichiers

Uploadez **tous** ces fichiers dans le dépôt, en respectant exactement cette structure :

```
huntrx-ar/
├── index.html
└── assets/
    ├── Mira.png
    ├── Rumi.png
    ├── Zoey.png
    └── Hunters_K-Pop.otf
```

**Méthode simple (sans Git) :**
1. Dans votre dépôt GitHub, cliquez **"uploading an existing file"**
2. Glissez-déposez `index.html`
3. Cliquez **"Commit changes"**
4. Créez le dossier `assets` : cliquez **"Add file" → "Create new file"**, tapez `assets/.gitkeep`, committez
5. Entrez dans `assets/` et uploadez les 4 fichiers (`Mira.png`, `Rumi.png`, `Zoey.png`, `Hunters_K-Pop.otf`)

---

### Étape 3 — Activer GitHub Pages

1. Dans votre dépôt, allez dans **Settings → Pages**
2. Sous "Source", sélectionnez **"Deploy from a branch"**
3. Choisissez la branche **`main`** et le dossier **`/ (root)`**
4. Cliquez **Save**
5. Attendez 1-2 minutes

Votre URL sera : `https://VOTRE-USERNAME.github.io/huntrx-ar/`

> ⚠️ **IMPORTANT** : L'app doit être servie en **HTTPS** pour accéder à la caméra. GitHub Pages active HTTPS automatiquement. ✅

---

## 📱 Utilisation de l'app

### Premier lancement (~30 secondes)
L'application compile automatiquement les personnages en réalité augmentée.  
Ce processus ne se fait qu'**une seule fois** — les prochaines fois, le chargement est quasi-instantané.

### Scan d'un topper
1. Ouvrez l'URL dans Safari (iOS) ou Chrome (Android)
2. Autorisez l'accès à la caméra
3. Pointez vers un topper de gâteau HuntrX
4. L'animation se déclenche automatiquement ✨

### Prise de photo
Appuyez sur le **bouton rond blanc** en bas de l'écran.  
La photo est sauvegardée dans vos téléchargements.

---

## 📐 Conseils pour les toppers

Pour un meilleur tracking AR :
- Imprimez les toppers en **couleur** sur papier mat ou cartonné
- Taille recommandée : **8 × 8 cm** minimum
- Éclairage : évitez les reflets brillants sur le topper
- Tenez le téléphone à **20-50 cm** du topper
- Le topper doit être **bien à plat** (pas courbé)

---

## 🎨 Personnages et couleurs

| Personnage | Couleur AR | Arme |
|-----------|-----------|------|
| **Mira** | Rose #FF2D9B | Faux arcane |
| **Rumi** | Violet #8B2FFF | Épée énergie |
| **Zoey** | Cyan #00E5FF | Cristaux |

---

## 🔧 Compatibilité

| Plateforme | Navigateur recommandé | Notes |
|-----------|----------------------|-------|
| iPhone / iPad | **Safari** | iOS 14.3+ |
| Android | **Chrome** | Android 8+ |
| Desktop | Chrome / Edge | Webcam requise |

---

## ❓ FAQ

**L'app ne reconnaît pas le topper**  
→ Assurez-vous que le topper est bien imprimé et visible entièrement dans le cadre. Essayez de vous rapprocher ou d'améliorer l'éclairage.

**La caméra ne s'ouvre pas**  
→ Vérifiez que le navigateur a la permission d'accéder à la caméra (Réglages → Safari/Chrome → Caméra).

**L'app est lente au premier chargement**  
→ Normal ! La compilation prend ~30 secondes uniquement la première fois. Ensuite elle est mise en cache.

**La photo est noire**  
→ Safari sur iOS peut bloquer la capture du canvas WebGL. Faites une capture d'écran native du téléphone (Volume haut + Bouton latéral sur iPhone).

---

*HuntrX AR — Fait avec ❤️ pour les fans*
