# 🌿 Crops — Site de l’association de jardinage

Crops est un projet WordPress développé dans le cadre d’un projet pédagogique.  
Il s’agit du site d’une association de jardinage proposant des événements (ateliers, sorties, concours, cours de botanique) avec un système d’inscription pour les membres.

Le projet est composé :

- 🎨 d’un **thème FSE personnalisé**
- 🔌 d’un **plugin de gestion d’événements**
- 🌱 d’un système d’inscription connecté aux comptes WordPress natifs**

---

## 🚀 Fonctionnalités principales

### 🎨 Thème FSE personnalisé

- Full Site Editing (templates en `.html`)
- Template dédiée `single-event`
- Block bindings pour afficher les champs personnalisés
- Design orienté nature & jardinage
- Header dynamique avec gestion de connexion utilisateur

---

### 🔌 Plugin Crops Events

Le plugin permet :

- ✅ Création d’un Custom Post Type `event`
- ✅ Champs personnalisés via **Advanced Custom Fields (version gratuite)**
- ✅ Gestion des inscriptions utilisateurs
- ✅ Table personnalisée pour stocker les inscriptions
- ✅ Bouton dynamique :
  - Se connecter  
  - S’inscrire  
  - Se désinscrire  
- ✅ Calcul automatique des places restantes
- ✅ Page “Mes événements” pour les abonnés
- ✅ Page admin “Voir les participants”
- ✅ Masquage de la barre d’administration pour les abonnés

---

## 👤 Gestion des rôles

- Les membres utilisent le rôle natif **Subscriber**
- Les abonnés :
  - ne voient pas la toolbar
  - ont accès à “Mes événements”
- Les administrateurs :
  - peuvent voir les participants
  - peuvent gérer les événements

---

## ⚙️ Installation

### Prérequis

- WordPress 6.5+
- PHP 8.0+
- Plugin **Advanced Custom Fields (gratuit)** installé et activé
