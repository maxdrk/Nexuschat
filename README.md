#  NexusChat

> Application de messagerie instantanée sécurisée — Projet de Fin d'Études (TFE)

NexusChat est une solution complète de messagerie instantanée sécurisée, développée comme projet final pour l'obtention du diplôme d'informatique en secondaire. Ce projet englobe le développement d'une application mobile, d'une API personnalisée et la gestion d'une infrastructure serveur complète.

---

## Statut du projet

**Archivé** :Les services backend et noms de domaine (nexuschat.derickexm.be) ne sont plus opérationnels. Le code est fourni tel quel sous licence Apache 2.0.

---

##  Architecture Système & Infrastructure

L'ensemble du projet repose sur une architecture robuste et auto-hébergée :

| Composant | Technologie |
|---|---|
| Hyperviseur | Proxmox VE |
| Système d'exploitation serveur | Linux (Debian/Ubuntu) |
| Backend API | Python (Flask / FastAPI) |
| Base de données | MariaDB |

---

##  Fonctionnalités Clés

###  Sécurité & Confidentialité

- **Chiffrement de bout en bout** — Les messages sont chiffrés via l'API avant stockage en base de données, avec gestion isolée des clés de déchiffrement.
- **Authentification sécurisée** — Alertes e-mail automatiques lors de tentatives de connexion.
- **Vérification de compte** — Validation par e-mail pour éviter les faux comptes.

###  Messagerie Avancée

- **Multimédia** — Support des messages textuels, intégration de GIFs via Giphy et partage de fichiers joints par URL.
- **Gestion Sociale** — Recherche d'utilisateurs et gestion complète des demandes d'amis (accepter / refuser / supprimer).
- **Notifications** — Flux centralisé pour ne manquer aucune interaction.

---

## Stack Technique

| Couche | Technologie |
|---|---|
| Frontend mobile | Flutter (Dart) — thèmes clair/sombre |
| Backend | Python — API REST |
| Base de données | MariaDB |
| Infrastructure | Proxmox VE (Virtualisation) |

---

## Organisation du Code Frontend
```
lib/
├── main.dart          # Point d'entrée de l'app et initialisation des services
├── login.dart         # Portail de connexion sécurisé
├── inscription.dart   # Portail d'inscription sécurisé
├── listechat.dart     # Vue d'ensemble des conversations actives
├── chat.dart          # Interface de discussion, polling des messages et chiffrement
├── contacts.dart      # Recherche d'utilisateurs et gestion des contacts
├── notifications.dart # Gestion des notifications
├── profil.dart        # Paramètres utilisateur, changement de mot de passe, suppression de compte
└── settings.dart      # Paramètres de l'application
```
---
##  Contexte du TFE

Ce projet est l'aboutissement d'une formation en informatique. Il démontre la capacité à concevoir une solution logicielle **Full Stack** complète :

- ⚙️ Configuration de l'hyperviseur **Proxmox VE**
- 🐍 Développement d'**API sécurisées en Python**
- 🗄️ Gestion de **bases de données MariaDB**
- 📱 Publication d'une **interface mobile Flutter**

---

### Documentation nexuschat 

TFE.pdf

**Développé par Maxime Derick** — Diplôme d'informatique · 2025