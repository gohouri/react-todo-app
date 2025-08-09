# ✅ React Todo List Application

Une application de liste de tâches moderne et fonctionnelle construite avec React et Vite. Cette application démontre les concepts fondamentaux de React avec une interface utilisateur élégante et intuitive.

## 🎯 Démonstration en Direct

🔗 **[Voir l'application en action](https://gohouri.github.io/react-todo-app/)**

## ✨ Fonctionnalités

- ➕ **Ajouter des tâches** facilement avec un formulaire intuitif
- ✅ **Marquer comme complètes** les tâches terminées
- 🗑️ **Supprimer des tâches** d'un simple clic
- 💾 **Sauvegarde automatique** avec localStorage
- 🎨 **Interface moderne** avec thème sombre élégant
- 📱 **Design responsive** adapté à tous les écrans
- ⚡ **Performance optimisée** avec Vite

## 🛠️ Technologies Utilisées

- **React 18** - Bibliothèque d'interface utilisateur moderne
- **Vite** - Outil de build ultra-rapide
- **CSS3** - Styles personnalisés avec variables CSS
- **LocalStorage** - Persistance des données côté client
- **ESLint** - Linting pour un code propre

## 🚀 Installation et Démarrage

### Prérequis

- Node.js (version 16 ou supérieure)
- npm, yarn, ou pnpm

### Installation

1. **Cloner le dépôt :**
```bash
git clone https://github.com/gohouri/react-todo-app.git
cd react-todo-app
```

2. **Installer les dépendances :**
```bash
npm install
# ou
yarn install
# ou
pnpm install
```

3. **Démarrer le serveur de développement :**
```bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
```

4. **Ouvrir l'application :**
   - Naviguez vers `http://localhost:5173` dans votre navigateur

## 🎮 Comment Utiliser

1. **➕ Ajouter une tâche** : Tapez votre tâche dans le champ de saisie et cliquez sur "Add" ou appuyez sur Entrée
2. **✅ Compléter une tâche** : Cliquez sur la case à cocher à côté de la tâche pour la marquer comme terminée
3. **🗑️ Supprimer une tâche** : Cliquez sur le bouton "Delete" pour supprimer définitivement la tâche
4. **💾 Sauvegarde automatique** : Vos tâches sont automatiquement sauvegardées et persistent entre les sessions

## 📁 Structure du Projet

```
react-todo-app/
├── src/
│   ├── App.jsx          # Composant principal de l'application
│   ├── NewTodoForm.jsx  # Formulaire d'ajout de tâches
│   ├── TodoList.jsx     # Liste des tâches
│   ├── TodoItem.jsx     # Composant individuel de tâche
│   ├── main.jsx         # Point d'entrée de l'application
│   └── styles.css       # Styles personnalisés
├── public/              # Assets statiques
├── dist/                # Build de production
├── docs/                # GitHub Pages deployment
├── index.html           # Template HTML
├── vite.config.js       # Configuration Vite
└── package.json         # Dépendances et scripts
```

## 🎨 Design et Interface

L'application présente :

- **🌙 Thème sombre moderne** avec des couleurs apaisantes
- **🎯 Interface minimaliste** et focalisée sur l'essentiel
- **✨ Animations fluides** pour une expérience utilisateur agréable
- **📱 Responsive design** qui s'adapte à tous les appareils
- **🔍 États visuels clairs** pour les tâches complétées (texte barré)

## 📚 Concepts React Démontrés

Ce projet illustre :

- **🏗️ Architecture en composants** React modulaire
- **🔄 Gestion d'état** avec le hook `useState`
- **⚡ Gestion d'événements** (onClick, onSubmit, onChange)
- **💾 Persistance des données** avec localStorage
- **🎨 Rendu conditionnel** pour l'affichage dynamique
- **🔄 Cycle de vie** avec `useEffect`
- **📝 Formulaires contrôlés** avec React

## 🚀 Scripts Disponibles

```bash
npm run dev          # Démarrer le serveur de développement
npm run build        # Construire pour la production
npm run preview      # Prévisualiser le build de production
npm run lint         # Lancer ESLint pour vérifier le code
```

## 🌐 Déploiement

L'application est automatiquement déployée sur GitHub Pages à chaque push sur la branche principale.

- **URL de production** : https://gohouri.github.io/react-todo-app/
- **Déploiement automatique** via GitHub Actions

## 🎓 Objectifs Pédagogiques

Ce projet a été créé dans le cadre du cours WDD430 pour démontrer :

- La maîtrise des concepts fondamentaux de React
- L'utilisation moderne des hooks React
- Les bonnes pratiques de développement
- La gestion d'état local et la persistance
- Le développement d'interfaces utilisateur interactives

## 🔗 Liens Utiles

- [React Documentation](https://react.dev/)
- [Vite Documentation](https://vitejs.dev/)
- [GitHub Pages](https://pages.github.com/)
- [CSS Variables Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)

## 📄 Licence

Ce projet a été créé à des fins éducatives dans le cadre du cours WDD430.
