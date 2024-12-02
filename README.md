# **Quiz Platform TF8**

## **Description**
La **Quiz Platform TF8** est une application multi-plateforme développée pour la chaîne de télévision TF8. Elle permet d’organiser des quiz interactifs en direct, accessibles aux participants en salle, aux téléspectateurs, et aux utilisateurs en ligne via des appareils Android ou un navigateur web.

---

## **Table des Matières**
1. [Fonctionnalités](#fonctionnalités)
2. [Architecture](#architecture)
3. [Technologies](#technologies)
4. [Installation et Configuration](#installation-et-configuration)

---

## **Fonctionnalités**
- **Participation multi-plateforme** : Accès via smartphone (Android) ou navigateur.
- **Gestion des Quiz** :
  - Création, modification, suppression des quiz.
  - Gestion des participants en temps réel.
- **Affichage interactif** :
  - Questions et réponses en temps réel.
  - Classements dynamiques et statistiques après chaque question.
- **Sécurité** :
  - Authentification sécurisée via Spring Security.
  - Stockage des données conforme au RGPD.

---

## **Architecture**
Le projet est divisé en plusieurs composants :

### **Répertoires**
- **Backend** : API REST et logique métier, développé en Java avec Spring Boot.
- **Frontend** : Interface utilisateur pour les téléspectateurs et administrateurs, développée en React.js.
- **Mobile** : Application Android pour la participation en mobilité.

---

## **Technologies**
- **Backend** :
  - Java 17, Spring Boot, Spring Data JPA, Spring Security.
  - WebSocket pour la communication en temps réel.
- **Frontend** :
  - React.js.
- **Mobile** :
  - Kotlin, Android SDK.
- **Base de Données** :
  - MySQL.

---

## **Installation et Configuration**

### **Pré-requis**
- **Environnement** :
  - JDK 17+
  - Node.js 18+
  - MySQL 8+
  - Android Studio (pour l’application mobile)
- **Outils** :
  - Maven, npm/yarn, Docker (optionnel pour l’environnement de test).

### **Étapes d’installation**

1. **Cloner les Dépôts**
   ```bash
   git clone https://github.com/hfreshnel/quiz-platform.git --recurse-submodules
2. **Configurer la Base de Données**
3. **Lancer le Backend**
4. **Lancer le Frontend**
5. **Lancer l’Application Mobile**