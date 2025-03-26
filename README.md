# 🐍 Snake Game React

Un jeu du serpent moderne et élégant construit avec React, TypeScript et Tailwind CSS. Ce projet propose plusieurs modes de jeu, une gestion des erreurs robuste, un suivi des meilleurs scores et des contrôles réactifs.

![Capture d'écran du jeu Snake](https://images.unsplash.com/photo-1635170929653-e8dbbd1a1c48?auto=format&fit=crop&q=80&w=800&h=400)

## ✨ Fonctionnalités

- 🎮 Trois vitesses de jeu :
  - 🐌 Mode Lent : Pour les débutants
  - 🚶 Mode Normal : L'expérience classique
  - 🐇 Mode Rapide : Pour les experts

- 🎯 Modes de jeu innovants :
  - Mode Classique : Le jeu traditionnel
  - Mode Portail : Traversez les murs pour réapparaître de l'autre côté
  - Mode Fantôme : Passez à travers votre corps

- 📱 Interface adaptative avec :
  - Contrôles tactiles
  - Support clavier (ZQSD/Flèches)
  - 3 tailles de terrain différentes

- 🏆 Fonctionnalités additionnelles :
  - Sauvegarde du meilleur score
  - Pause (touche Espace)
  - Animations fluides
  - Interface moderne avec Tailwind CSS

## 🛠️ Technologies Utilisées

- React 18
- TypeScript
- Tailwind CSS
- Vite
- Lucide React (icônes)

## 📦 Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-nom/snake-game-react.git
   ```

2. Accédez au répertoire du projet :
   ```bash
   cd snake-game-react
   ```

3. Installez les dépendances :
   ```bash
   npm install
   ```

4. Lancez le serveur de développement :
   ```bash
   npm run dev
   ```

## 🎮 Comment Jouer

1. Utilisez les touches ZQSD ou les flèches directionnelles pour diriger le serpent
2. Mangez les pommes pour grandir et augmenter votre score
3. Évitez les collisions selon le mode de jeu choisi
4. Appuyez sur Espace pour mettre le jeu en pause

## 🚀 Déploiement

1. Construisez le projet :
   ```bash
   npm run build
   ```

2. Les fichiers de production seront générés dans le dossier `dist`

3. Déployez sur votre plateforme préférée :

   ### Netlify
   - Connectez votre dépôt GitHub
   - Commande de build : `npm run build`
   - Dossier de publication : `dist`

   ### Vercel
   - Importez votre dépôt
   - La configuration sera détectée automatiquement
   - Cliquez sur déployer

## 🔧 Structure du Projet

```
src/
├── App.tsx        # Composant principal du jeu
├── index.css      # Styles globaux
└── main.tsx       # Point d'entrée
```

## 🤝 Contribution

1. Forkez le projet
2. Créez votre branche (`git checkout -b feature/NouvelleFonctionnalite`)
3. Committez vos changements (`git commit -m 'Ajout d'une nouvelle fonctionnalité'`)
4. Poussez vers la branche (`git push origin feature/NouvelleFonctionnalite`)
5. Ouvrez une Pull Request

## 📝 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 🙏 Remerciements

- Inspiré du jeu Snake classique
- Icônes fournies par [Lucide React](https://lucide.dev)
- Construit avec [Vite](https://vitejs.dev)