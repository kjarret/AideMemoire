<h1 align="center">Projet Aide-Mémoire</h1>

<p align="center">
  <img src="https://github.com/kjarret/AideMemoire/blob/main/www/img/logo.png" width="200" height="200">
</p>

## BTS Systèmes Numériques - Option A (IR) - Session 2023

### 📍 Groupement Académique: Nancy-Metz

---

### 🚀 Objectif

L'objectif principal de ce projet est de développer un support numérique pour aider les personnes âgées ou atteintes de troubles cognitifs comme la maladie d'Alzheimer à garder leurs repères temporels grâce à des informations fondamentales affichées de manière répétitive.

### 💡 Caractéristiques Principales

- **Fonctionnalités**:
  - Affichage de la date et de l'heure (horloge digitale/analogique)
  - Éphéméride personnalisé (anniversaires, rendez-vous)
  - Gestion à distance et sans interaction requise de l'utilisateur

- **Technologie**:
  - Utilisation d'une tablette Android ou d'un écran via une Raspberry Pi
  - Synchronisation avec Google Agenda pour la mise à jour des événements

### 🛠 Spécifications Techniques

- **Matériel**: Raspberry Pi 3/4, écran ou tablette Android
- **Logiciel**: Applications développées pour la récupération et l'affichage des informations
- **Langages et Outils**: Choix libre adapté au projet

### 📅 Planning

- Janvier: Distribution du projet
- Février-Mars: Première revue
- Mai: Seconde revue
- Juin: Revue finale et restitution

---

## 🚀 Lancement du projet avec Apache Cordova

Suivez ces étapes pour configurer et lancer votre projet Aide-Mémoire développé avec Apache Cordova.

### 1. Prérequis

Assurez-vous que Node.js et npm sont installés sur votre machine. Apache Cordova nécessite Node.js pour fonctionner. Vous pouvez télécharger Node.js à partir de [Node.js Official Website](https://nodejs.org/).

### 2. Installation de Cordova

Ouvrez un terminal et exécutez la commande suivante pour installer Cordova globalement sur votre système :

```npm install -g cordova```

```cd ProjetAideMemoire```

```cordova platform add android```

```cordova platform add ios```

### 3. Installation des Dépendances
Assurez-vous que toutes les dépendances du projet sont installées :

```npm install```

### 4. Construction et Lancement
Construisez votre application pour les plateformes ajoutées :

```cordova build```

Pour lancer l'application, utilisez :

```cordova run android```

Remplacez android par la plateforme de votre choix (par exemple, ios si vous ciblez iOS et que vous avez un Mac).

***Ce projet vise à améliorer le quotidien des personnes nécessitant une aide pour se rappeler des informations essentielles de leur vie quotidienne.***
