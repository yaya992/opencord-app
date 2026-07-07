# OpenCord

## Client desktop officiel OpenCord

Une application rapide, légère et optimisée pour utiliser OpenCord depuis Windows, macOS et Linux.

---

## ✨ Présentation

OpenCord est une application desktop basée sur **Tauri** permettant d'accéder à OpenCord avec une interface native.

Objectifs :

- 🚀 Démarrage rapide
- 🖥️ Application dédiée
- 🔒 Connexion sécurisée au service officiel
- ⚡ Meilleure intégration avec le système
- 🎮 Préparation pour les futures fonctions avancées (partage d'écran, optimisation GPU, etc.)

---

Formats disponibles :

| Système | Format |
|---|---|
| Windows | `.exe` / `.msi` |
| macOS | `.dmg` |
| Linux | `.AppImage` / `.deb` |

---

## 🌐 Liens officiels

Site :

https://opencord.fr

Connexion :

https://opencord.fr/auth/login

---

## 🛠️ Technologies

OpenCord utilise :

- **Tauri** — application desktop légère
- **Rust** — couche native
- **Node.js** — environnement JavaScript
- **Vite** — système de build
- **Tailwind CSS** — interface utilisateur

---

## 🏗️ Installation pour développeurs

### Prérequis

Installer :

- Node.js 22+
- Rust
- Cargo
- Les dépendances Tauri

Installation :

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
│   ├── Code natif Rust
│   └── Icônes application
│
└── .github/
    └── workflows/
        └── Build automatique
```

---

## 🔄 Compilation automatique

Les versions sont générées automatiquement avec GitHub Actions.

Processus :

```
Modification du code
        ↓
GitHub Actions
        ↓
Build Windows
Build macOS
Build Linux
        ↓
GitHub Release
```

---

## 🔐 Sécurité

OpenCord :

* ✅ est open source
* ✅ utilise uniquement les services officiels OpenCord
* ✅ ne contient aucun logiciel tiers caché
* ✅ permet la vérification du code source

Le code est public afin de garantir la transparence du projet.

---

## 🐛 Signaler un problème

Pour signaler un bug :

1. Ouvrez une issue GitHub
2. Indiquez votre système d'exploitation
3. Indiquez la version d'OpenCord utilisée
4. Ajoutez une description du problème

---

## 🤝 Contribution

Les contributions sont les bienvenues.

Vous pouvez :

* proposer des améliorations ;
* signaler des bugs ;
* participer au développement.

---

## 📜 Licence

Licence : à définir.

---

Merci de contribuer au développement d'OpenCord !
