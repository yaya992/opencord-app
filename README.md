```md
# OpenCord

<p align="center">
  <img src="src-tauri/icons/icon.png" width="128" />
</p>

<h3 align="center">
Client desktop officiel OpenCord
</h3>

<p align="center">
Une application rapide, légère et optimisée pour accéder à OpenCord depuis Windows, macOS et Linux.
</p>

---

## ✨ Présentation

OpenCord est une application desktop basée sur **Tauri** permettant d'utiliser OpenCord dans une interface native.

L'objectif est de fournir une meilleure expérience qu'un simple navigateur :

- 🚀 démarrage rapide
- 🖥️ application dédiée
- 🔒 connexion sécurisée au site officiel
- ⚡ meilleure intégration système
- 🎮 préparation pour les fonctionnalités avancées (partage d'écran, optimisation GPU, etc.)

---

## 📦 Téléchargement

Les versions officielles sont disponibles ici :

➡️ **GitHub Releases :**
```

https://github.com/VOTRE_COMPTE/OpenCord/releases

```

Versions disponibles :

| Système | Format |
|---|---|
| Windows | `.exe` / `.msi` |
| macOS | `.dmg` |
| Linux | `.AppImage` / `.deb` |

---

## 🌐 Site officiel

Site :
```

https://opencord.fr

```

Connexion :
```

https://opencord.fr/auth/login

````

---

## 🛠️ Technologies utilisées

OpenCord utilise :

- [Tauri](https://tauri.app/) — application desktop légère
- Node.js — environnement JavaScript
- Vite — build frontend
- Tailwind CSS — interface utilisateur
- Rust — couche native Tauri

---

## 🏗️ Compilation locale

### Prérequis

Installer :

- Node.js 22+
- Rust
- Cargo
- Les dépendances Tauri

Puis :

```bash
npm install
````

Lancer en développement :

```bash
npm run tauri dev
```

Créer une version :

```bash
npm run tauri build
```

---

## 📁 Structure du projet

```
OpenCord/
│
├── src/
│   └── Interface utilisateur
│
├── src-tauri/
│   ├── Configuration Tauri
│   ├── Code natif
│   └── Icônes application
│
└── .github/
    └── workflows/
        └── Build automatique
```

---

## 🔄 Build automatique

Les builds sont générés automatiquement avec GitHub Actions :

```
Push du code
      ↓
GitHub Actions
      ↓
Windows Build
macOS Build
Linux Build
      ↓
GitHub Release
```

---

## 🔐 Sécurité

OpenCord :

✅ est open source
✅ utilise uniquement le domaine officiel OpenCord
✅ ne collecte aucune donnée personnelle inutile
✅ ne contient aucun logiciel tiers caché

Le code source complet est disponible pour permettre à chacun de vérifier le fonctionnement de l'application.

---

## 🐛 Signaler un problème

Si vous trouvez un bug ou un problème :

1. Ouvrez une issue GitHub
2. Décrivez le problème
3. Ajoutez votre système d'exploitation et la version utilisée

---

## 📜 Licence

Ce projet est distribué sous licence :

```
À définir
```

---

## ❤️ Contribution

Les contributions sont les bienvenues.

Vous pouvez :

* proposer des améliorations ;
* signaler des bugs ;
* contribuer au code.

Merci de participer au développement d'OpenCord !

```
```
