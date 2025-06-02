# 🤖💖 Robot Fille - Résolveur de Labyrinthe

Une implémentation interactive et visuelle d'algorithmes de recherche en Intelligence Artificielle, où une petite robot fille navigue dans un labyrinthe pour trouver la sortie !

## 🚀 Démo en Direct

**[▶️ Essayer l'Application](https://robot-in-mazee.onrender.com)**


## 📋 Description du Projet

Ce projet a été développé pour démontrer le fonctionnement de différents algorithmes de recherche à travers une simulation interactive et esthétique.

### 🎯 Objectif
Aider une petite robot fille à naviguer dans un labyrinthe 5x5 pour atteindre la sortie en utilisant différents algorithmes de recherche.

## ✨ Fonctionnalités

### 🔍 Algorithmes Implémentés
- **BFS (Breadth-First Search)** - Exploration niveau par niveau, garantit le chemin le plus court
- **DFS (Depth-First Search)** - Exploration en profondeur, rapide mais pas forcément optimal
- **A*** - Recherche guidée par heuristique, solution optimale et efficace

### 🎨 Interface Utilisateur
- **Design moderne et féminin** avec couleurs roses et violettes
- **Mode sombre/clair** avec transition fluide
- **Animations fluides** pour visualiser l'exploration en temps réel
- **Interface responsive** compatible mobile et desktop
- **Statistiques détaillées** (temps d'exécution, nœuds explorés, longueur du chemin)

### 📊 Visualisation
- Animation en temps réel de l'exploration
- Chemin solution mis en évidence avec effets visuels
- Légende colorée pour comprendre la visualisation
- Messages d'encouragement interactifs

## 🛠️ Technologies Utilisées

- **HTML5** - Structure de l'application
- **CSS3** - Styling avancé avec gradients, animations et glassmorphism
- **JavaScript Vanilla** - Logique des algorithmes et interactions
- **Render** - Déploiement et hébergement

## 📐 Spécifications Techniques

### Structure du Labyrinthe
```
8  9  🧱 11 🧱
10 🧱 12 13 🧱
6  5  7  14 17
3  2  4  🧱 🧱
A  1  15 16 B
```

- **Point de départ :** A (position du robot)
- **Objectif :** B (sortie du labyrinthe)
- **Grille :** 5x5 avec murs (🧱) et chemins numérotés

### Heuristique A*
| Node | A | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10| 11| 12| 13| 14| 15| 16| 17| B |
|------|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| h(n) | 8 | 6 | 6 | 6 | 7 | 4 |12 | 7 |15 |18 | 6 | 8 | 6 | 5 | 4 | 8 | 6 | 3 | 0 |

## 🚀 Utilisation

1. **Visitez l'application** : [robot-in-mazee.onrender.com](https://robot-in-mazee.onrender.com)
2. **Choisissez un algorithme** : BFS, DFS ou A*
3. **Observez l'exploration** en temps réel
4. **Analysez les statistiques** et comparez les performances
5. **Basculez entre les thèmes** sombre et clair
6. **Réinitialisez** pour tester un autre algorithme

## 📱 Compatibilité

- ✅ Navigateurs modernes (Chrome, Firefox, Safari, Edge)
- ✅ Appareils mobiles et tablettes
- ✅ Ordinateurs de bureau
- ✅ Mode sombre et clair

## 📊 Métriques de Performance

L'application affiche en temps réel :
- **Nœuds Explorés** : Nombre de cellules visitées
- **Longueur du Chemin** : Nombre d'étapes de la solution
- **Temps d'Exécution** : Performance de l'algorithme
- **Algorithme Utilisé** : BFS, DFS ou A*

## 🤝 Contribution

Ce projet est développé dans un cadre académique. Les suggestions d'amélioration sont les bienvenues !

## 👩‍💻 Auteur

**Yasmine Roukas** - Étudiante en Intelligence Artificielle à l'ESTIN

---

<div align="center">

**[🚀 Lancer l'Application](https://robot-in-mazee.onrender.com)**

*Aidez notre petite robot fille à trouver son chemin ! 🤖💖*

![Made with Love](https://img.shields.io/badge/Made%20with-💖-ff69b4?style=for-the-badge)

</div>
