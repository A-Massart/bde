# BDE - Site Web du Bureau des Élèves

Bienvenue sur le projet de site web officiel du Bureau des Élèves (BDE). Cette plateforme sert de centre d'information pour les étudiants afin de rester informés des événements à venir, accéder aux archives des événements passés et s'engager avec la communauté BDE.

## 🎯 Aperçu du Projet

Le site web BDE vise à :
- Afficher les événements à venir organisés par le BDE dans l'ordre chronologique
- Fournir une archive des événements passés avec les retours des étudiants, témoignages, évaluations et albums photo
- Offrir un système de gestion de contenu facile pour les non-développeurs
- Utiliser des outils et hébergement gratuits

## ✨ Fonctionnalités

### Événements à Venir
- **Affichage Chronologique** : Les événements sont organisés par date, montrant ce qui arrive ensuite
- **Détails des Événements** : Date, heure, lieu, description et informations d'inscription
- **Affiches d'Événements** : Affichage des mêmes affiches utilisées pour les annonces dans le bâtiment
- **Appel Visuel** : Interface moderne et claire mettant en évidence le prochain événement

### Archives d'Événements
- **Dépôt d'Événements Passés** : Historique complet des événements BDE
- **Affiches d'Événements** : Archive de toutes les affiches d'événements pour référence historique
- **Retours des Étudiants** : Témoignages et évaluations des participants aux événements
- **Albums Photo** : Galeries de souvenirs pour chaque événement
- **Recherche et Filtrage** : Navigation facile dans les événements passés

### Gestion de Contenu
- **Basé sur Markdown** : Fichiers Markdown simples pour chaque événement
- **Téléchargement d'Images Direct** : Glisser-déposer les images directement dans l'éditeur GitHub
- **Reconstruction Automatique** : Le site se met à jour automatiquement lors des changements de contenu
- **Contrôle de Version** : Historique complet de tous les changements de contenu
- **Convivial pour les Non-Développeurs** : Édition visuelle avec l'interface web de GitHub

## 🛠️ Stack Technologique

### Solutions Gratuites Recommandées

#### Hébergement et Développement de Site Web
- **GitHub Pages + Jekyll** (Solution complète)
  - Hébergement de site statique gratuit
  - Support Jekyll intégré pour les fichiers Markdown
  - Génération automatique de site à partir de Markdown
  - Support de domaine personnalisé
  - Intégration du contrôle de version
  - Aucun hébergement externe nécessaire

#### Gestion de Contenu
- **Fichiers Markdown GitHub**
  - Fichiers Markdown simples pour chaque événement
  - Téléchargement d'images direct via l'éditeur web GitHub
  - Reconstruction automatique du site lors des commits
  - Contrôle de version pour tous les changements de contenu
  - Gratuit et intégré à l'hébergement
  - Très convivial pour les non-développeurs

#### Framework de Site Web
- **Jekyll** (Intégré à GitHub Pages)
  - Support Markdown natif
  - Génération automatique de site
  - Intégration GitHub Pages intégrée
  - Aucune configuration supplémentaire requise
  - Hébergement gratuit inclus

## 📋 État d'Avancement du Projet

### ✅ Phase 1 : Fondation (TERMINÉE)
- [x] Configurer le dépôt Git local
- [x] Créer la structure de base du site Jekyll
- [x] Configurer l'organisation des fichiers Markdown (`_events/` et `_archive/`)
- [x] Configurer Jekyll avec les collections et layouts

### ✅ Phase 2 : Fonctionnalités Principales (TERMINÉE)
- [x] Implémenter l'affichage des événements à venir
- [x] Créer le système d'archive d'événements
- [x] Concevoir la mise en page responsive
- [x] Ajouter le style de base et l'identité visuelle

### ✅ Phase 3 : Gestion de Contenu (TERMINÉE)
- [x] Créer la structure de fichiers Markdown pour les événements
- [x] Configurer la reconstruction automatique du site
- [x] Créer un workflow d'édition Markdown simple
- [x] Tester le workflow avec des événements d'exemple

### ✅ Phase 4 : Fonctionnalités Avancées (TERMINÉE)
- [x] Créer des posters temporaires pour les événements
- [x] Implémenter l'affichage des posters sur les pages d'événements
- [x] Configurer la génération de pages individuelles
- [x] Optimiser les URLs (sans extension .md)

### 🔄 Phase 5 : Déploiement (EN COURS)
- [ ] Créer le dépôt GitHub
- [ ] Pousser le code vers GitHub
- [ ] Activer GitHub Pages
- [ ] Tester le déploiement en production

## 🎨 Considérations de Design

### Expérience Utilisateur
- **Mobile-First** : Design responsive pour tous les appareils
- **Chargement Rapide** : Images optimisées et dépendances minimales
- **Navigation Intuitive** : Structure de menu claire et fonctionnalité de recherche
- **Accessibilité** : Conformité WCAG pour un design inclusif

### Identité Visuelle
- **Marque BDE** : Utilisation cohérente des couleurs, polices et logo
- **Centré sur les Événements** : Hiérarchie visuelle mettant l'accent sur les événements à venir
- **Intégration d'Affiches** : Affichage transparent des affiches d'événements physiques
- **Riche en Photos** : Mettre en valeur les souvenirs d'événements et l'esprit communautaire

## 📊 Structure des Données

### Modèle de Données d'Événement (Format Markdown)
```markdown
---
# _events/2025-09-15-soiree-bienvenue.md (événements à venir)
# _archive/2025-09-15-soiree-bienvenue.md (événements passés)
titre: "Soirée de Bienvenue BDE"
date: 2025-09-15
heure: "19:00"
lieu: "Centre Étudiant - Salle Polyvalente"
poster: "assets/images/posters/soiree-bienvenue-2025.svg"
url_inscription: "https://forms.gle/example1"
---

# Soirée de Bienvenue BDE

Rejoignez-nous pour la grande soirée de bienvenue du BDE ! Une occasion parfaite pour rencontrer vos nouveaux camarades et découvrir toutes les activités que nous organisons cette année.

## Détails de l'Événement
- **Date** : 15 septembre 2025
- **Heure** : 19h00
- **Lieu** : Centre Étudiant - Salle Polyvalente
- **Inscription** : [Inscrivez-vous ici](https://forms.gle/example1)

## Au Programme
- 🎵 **Musique live** avec des groupes étudiants
- 🍕 **Buffet** et boissons
- 🎮 **Jeux** et animations
- 🎁 **Tombola** avec de nombreux lots
- 💃 **Soirée dansante** jusqu'à minuit

## Photos (pour les archives)
![Photo de l'Événement 1](assets/images/events/soiree-bienvenue-1.jpg)
![Photo de l'Événement 2](assets/images/events/soiree-bienvenue-2.jpg)

## Retours des Étudiants (pour les archives)
- **Marie** : "Événement incroyable ! ⭐⭐⭐⭐⭐"
- **Pierre** : "Super ambiance et activités amusantes ! ⭐⭐⭐⭐⭐"
```

### Structure des Fichiers
```
bde_alice/
├── _config.yml              # Configuration Jekyll
├── _layouts/                # Templates HTML
│   ├── default.html         # Layout principal
│   └── event.html           # Layout pour les événements
├── _plugins/                # Générateurs personnalisés
│   └── event_pages.rb       # Générateur de pages d'événements
├── _events/                 # Événements à venir
│   ├── 2025-09-15-soiree-bienvenue.md
│   ├── 2025-09-22-tournoi-football.md
│   ├── 2025-09-28-cinema-en-plein-air.md
│   └── 2025-09-30-atelier-cuisine.md
├── _archive/                # Événements passés
├── assets/                  # Ressources statiques
│   ├── css/style.css        # Styles CSS
│   └── images/              # Images et posters
│       ├── posters/         # Affiches d'événements
│       └── events/          # Photos d'événements
├── index.md                 # Page d'accueil
├── events.md                # Page liste des événements
├── archive.md               # Page archives
└── Gemfile                  # Dépendances Ruby
```

## 🔧 Configuration de Développement

### Prérequis
- Git
- Ruby (version 2.7.0 ou supérieure)
- Compte GitHub
- Compréhension de base de Markdown (optionnel - GitHub a un éditeur visuel)

### Installation et Test Local

#### 1. Cloner le Projet
```bash
# Cloner le dépôt (une fois créé sur GitHub)
git clone https://github.com/votre-nom-utilisateur/bde-website.git
cd bde-website
```

#### 2. Installation des Dépendances
```bash
# Installer les gems Jekyll
bundle install
```

#### 3. Démarrage du Serveur Local
```bash
# Démarrer le serveur de développement
bundle exec jekyll serve --host 0.0.0.0 --port 4000
```

#### 4. Accès au Site
- **URL locale** : http://localhost:4000
- **URL réseau** : http://0.0.0.0:4000 (accessible depuis d'autres appareils)

### Pages Disponibles
- **Accueil** : http://localhost:4000/
- **Événements** : http://localhost:4000/events/
- **Archives** : http://localhost:4000/archive/
- **Événements individuels** :
  - http://localhost:4000/events/2025-09-15-soiree-bienvenue/
  - http://localhost:4000/events/2025-09-22-tournoi-football/
  - http://localhost:4000/events/2025-09-28-cinema-en-plein-air/
  - http://localhost:4000/events/2025-09-30-atelier-cuisine/

### Commandes Utiles
```bash
# Reconstruire le site
bundle exec jekyll build

# Nettoyer et reconstruire
rm -rf _site && bundle exec jekyll build

# Vérifier la configuration
bundle exec jekyll doctor

# Arrêter le serveur
Ctrl+C
```

## 📝 Guide de Gestion de Contenu

### Pour les Membres BDE (Non-Développeurs)

1. **Ajouter de Nouveaux Événements**
   - Créer un nouveau fichier Markdown dans le dossier `_events/`
   - Utiliser le format de nom de fichier : `YYYY-MM-DD-nom-evenement.md`
   - Remplir les métadonnées (front matter) en haut :
     ```markdown
     ---
     titre: "Soirée de Bienvenue BDE"
     date: 2024-01-15
     heure: "19:00"
     lieu: "Centre Étudiant"
     statut: "upcoming"
     url_inscription: "https://..."
     ---
     ```
   - Écrire la description de l'événement en Markdown
   - **Télécharger les images directement** : Glisser-déposer l'affiche dans l'éditeur
   - GitHub télécharge automatiquement les images et crée le bon chemin
   - Commiter les changements - le site se reconstruit automatiquement

2. **Archiver les Événements Passés**
   - Déplacer le fichier de l'événement du dossier `_events/` vers le dossier `_archive/`
   - Ajouter une section "Retours des Étudiants" avec les témoignages
   - Télécharger les photos de l'événement en les glissant dans l'éditeur
   - Commiter les changements pour mettre à jour l'archive

3. **Gérer le Contenu**
   - Utiliser l'interface web de GitHub avec l'éditeur Markdown visuel
   - Glisser-déposer les images directement dans l'éditeur
   - Utiliser le formatage Markdown pour le texte enrichi (gras, liens, listes)
   - Collaborer grâce aux fonctionnalités intégrées de GitHub
   - Prévisualiser les changements avant de commiter

## 🚀 Déploiement

### Déploiement GitHub Pages
1. **Créer le dépôt GitHub** :
   ```bash
   # Créer un nouveau dépôt sur GitHub (ex: bde-website)
   ```

2. **Pousser le code** :
   ```bash
   git remote add origin https://github.com/votre-username/bde-website.git
   git branch -M main
   git push -u origin main
   ```

3. **Activer GitHub Pages** :
   - Aller dans Settings > Pages
   - Source : Deploy from a branch
   - Branch : main
   - Folder : / (root)

4. **Accès au site** :
   - URL : https://votre-username.github.io/bde-website/
   - Le site se met à jour automatiquement à chaque push

### Configuration du Domaine Personnalisé (Optionnel)
1. Ajouter un fichier `CNAME` avec votre domaine
2. Configurer les DNS de votre domaine
3. Activer HTTPS dans les paramètres GitHub Pages


## 🤝 Contribution

### Pour les Développeurs
1. Forker le dépôt
2. Créer une branche de fonctionnalité
3. Apporter vos modifications
4. Tester soigneusement
5. Soumettre une pull request

### Pour les Membres BDE
1. Utiliser GitHub pour la gestion de contenu
2. Signaler les problèmes via les issues GitHub
3. Fournir des retours sur l'expérience utilisateur
4. Suggérer de nouvelles fonctionnalités

## 📞 Support

### Problèmes Techniques
- Créer des issues GitHub pour les bugs ou problèmes techniques
- Consulter la documentation pour les solutions communes
- Contacter l'équipe de développement pour les problèmes complexes

### Gestion de Contenu
- Se référer au guide de gestion de contenu
- Contacter la direction BDE pour les problèmes d'accès
- Utiliser la documentation d'aide de GitHub

## 📄 Licence

Ce projet est open source et disponible sous la [Licence MIT](LICENSE).

## 🙏 Remerciements

- Équipe BDE pour la vision du projet
- Communauté étudiante pour les retours et suggestions
- Communauté open source pour les outils et ressources

---

## 🎯 Fonctionnalités Implémentées

### ✅ Fonctionnalités Principales
- **Site Jekyll** entièrement fonctionnel
- **4 événements d'exemple** avec posters temporaires
- **Pages individuelles** pour chaque événement
- **URLs propres** sans extension .md
- **Design responsive** et moderne
- **Navigation intuitive** entre les sections

### ✅ Posters d'Événements
- **Soirée de Bienvenue** - Dégradé bleu/violet avec ballons
- **Tournoi de Football** - Dégradé vert avec terrain de foot
- **Cinéma en Plein Air** - Dégradé sombre avec étoiles
- **Atelier Cuisine** - Dégradé rouge/orange avec ingrédients

### ✅ Structure Technique
- **Collections Jekyll** pour événements et archives
- **Générateur personnalisé** pour les pages d'événements
- **Layouts HTML** optimisés
- **CSS responsive** avec design moderne
- **Support Markdown** complet

---

**Dernière Mise à Jour** : Septembre 2025  
**Version** : 1.0.0  
**Statut** : Prêt pour Déploiement