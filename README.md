<p align="center">
  <img src="assets/screenshots/wsselni.png" alt="Wasselni Logo" width="400" />
</p>



<p align="center">
  <strong>La solution de mobilité intelligente pour un covoiturage simplifié.</strong>
</p>

---

### 🌟 Présentation
**Wasselni** est une solution de mobilité intelligente conçue pour transformer l'expérience du covoiturage. Développée initialement en **2023** et ayant bénéficié d'une mise à jour majeure en **2026**, l'application met en relation des conducteurs ayant des places libres avec des passagers voyageant dans la même direction, offrant ainsi une alternative de transport économique, écologique et conviviale.

### 📝 À propos du projet
Le projet est né d'un constat simple : la difficulté croissante des déplacements urbains et interurbains, couplée à l'augmentation des coûts de transport. **Wasselni** (qui signifie *"Emmène-moi"* ou *"Dépose-moi"* en arabe) répond à cette problématique en proposant une plateforme sécurisée et intuitive.

### 🚀 Pourquoi Wasselni ?
* **💰 Économie :** Réduction des frais de carburant et de trajet pour tous les utilisateurs.
* **🌱 Écologie :** Moins de voitures sur la route pour une empreinte carbone réduite.
* **🤝 Social :** Créer du lien entre les usagers d'un même itinéraire.
* **🛡️ Sécurité :** Profils vérifiés et système de notation pour une confiance mutuelle.

---
## 🛠️ Stack Technique

L'application **Wasselni** est bâtie sur un écosystème performant et scalable, utilisant les dernières versions des technologies de développement mobile.

### Frontend (Mobile)
* **Framework :** [React Native](https://reactnative.dev/) (v0.81) via **Expo SDK 54**.
* **Langage :** [TypeScript](https://www.typescriptlang.org/) - Pour un code robuste et typé.
* **Gestion d'état :** [Redux Toolkit](https://redux-toolkit.js.org/) - Centralisation des données de l'application.
* **Navigation :** [React Navigation](https://reactnavigation.org/) (Stack & Bottom Tabs) - Navigation fluide entre les écrans.
* **Interface UI :** [React Native Elements (RNEUI)](https://reactnativeelements.com/) & [Vector Icons](https://icons.expo.fyi/) - Design moderne et consistant.
* **Formulaires :** [Formik](https://formik.org/) - Gestion simplifiée des formulaires et de la validation.

### Backend & Services
* **BaaS (Backend as a Service) :** [Firebase](https://firebase.google.com/) (v12) - Gestion de la base de données en temps réel et de l'authentification.
* **Stockage Local :** [Async Storage](https://react-native-async-storage.github.io/async-storage/) - Persistance des données utilisateur sur l'appareil.
* **Multimédia :** [Expo Image Picker](https://docs.expo.dev/versions/latest/sdk/imagepicker/) - Pour la sélection des photos de profil ou de véhicules.

---

## 📂 Architecture du Projet

Le projet suit une structure modulaire pour séparer la logique de navigation, les composants réutilisables et les écrans de l'application.


```text
my-app-v3/
├── 📱 app/                 # Configuration Expo Router & Layouts principaux
├── 📍 navigators/          # Configuration de la navigation (Stacks & Tabs)
├── 🖼️ Screens/             # Écrans de l'application (Auth, Trajets, Profil...)
│   ├── Auth/               # Connexion, Inscription, Réinitialisation
│   ├── Trajets/            # Recherche, Annonce, Détails, Résultats
│   └── User/               # Profil, Véhicule, Modifier, Notifications
├── 🧩 Components/          # Composants UI réutilisables et thématiques
├── 🎨 constants/           # Thèmes, couleurs et styles globaux
├── ⚓ hooks/               # Custom hooks (thèmes, gestion des couleurs)
├── 📁 assets/              # Ressources statiques (Images, Logos, Icônes)
├── 🔥 firebase.js          # Configuration et initialisation Firebase
└── ⚙️ package.json         # Dépendances et scripts du projet
```
---

## 🚀 Fonctionnalités Clés
L'application **Wasselni** offre une expérience complète pour les conducteurs et les passagers, articulée autour de quatre piliers principaux :

### 🔐 Gestion des Utilisateurs (Auth)
* **Authentification sécurisée :** Inscription, connexion et réinitialisation de mot de passe via Firebase.
* **Profil Personnalisé :** Gestion des informations personnelles, photo de profil et historique.
* **Garage Virtuel :** Enregistrement et gestion des véhicules pour les conducteurs.

### 🚗 Covoiturage & Trajets
* **Recherche Avancée :** Filtrage des trajets par destination, date et préférences.
* **Publication d'Annonces :** Création simple de trajets pour les conducteurs (lieu de départ, arrivée, prix, places disponibles).
* **Détails des Trajets :** Consultation approfondie des offres (horaires, type de véhicule, avis).
* **Mes Trajets :** Suivi en temps réel des trajets réservés ou publiés.

### 🔔 Expérience Utilisateur
* **Système de Notifications :** Alertes en temps réel pour les réservations et les mises à jour de trajets.
* **Interface Adaptative :** Support du mode clair/sombre grâce à des Hooks personnalisés (`use-color-scheme`).
* **Navigation Intuitive :** Menu par onglets (Bottom Tabs) pour un accès rapide aux fonctions essentielles.

### 🛠️ Administration & Paramètres
* **Modification de profil :** Mise à jour fluide des données utilisateur.
* **Gestion du Thème :** Paramètres personnalisables via `constants/theme.ts`.

---

## 📸 Galerie Complète & Évolution (2023 ➔ 2026)

L'application a été entièrement repensée. Voici l'intégralité des interfaces de la **Version 1 (2023)** et de la **Nouvelle Version (2026)**.
### 🆕 Version Actuelle (2026)
*Une interface moderne optimisée pour l'expérience utilisateur.*

| Recherche & Accueil | Résultats de Recherche | Détails Trajet (Mes Trajets) |
|:---:|:---:|:---:|
| <img src="assets/screenshots/rechercheV2.PNG" width="200" /> | <img src="assets/screenshots/resultatRechercheV2.PNG" width="200" /> | <img src="assets/screenshots/detailsResultatV2.PNG" width="200" /> |

| Profil Utilisateur | Modifier Profil | Détails Mes Trajets |
|:---:|:---:|:---:|
| <img src="assets/screenshots/profilV2.PNG" width="200" /> | <img src="assets/screenshots/modifierV2.PNG" width="200" /> | <img src="assets/screenshots/detailsMesTrajetsV2.PNG" width="200" /> |

| Inscription | Connexion | Mot de passe oublié |
|:---:|:---:|:---:|
| <img src="assets/screenshots/inscriptionV2.PNG" width="200" /> | <img src="assets/screenshots/ConnexionV2.PNG" width="200" /> | <img src="assets/screenshots/mdpV2.PNG" width="200" /> |

| Ajouter un trajet | Mes Annonces | Mes Trajets |
|:---:|:---:|:---:|
| <img src="assets/screenshots/ajouterV2.PNG" width="200" /> | <img src="assets/screenshots/mesAnnoncesV2.PNG" width="200" /> | <img src="assets/screenshots/mestrajetsV2.PNG" width="200" /> |

| Notifications | Véhicule | Splash Screen |
|:---:|:---:|:---:|
| <img src="assets/screenshots/notifV2.PNG" width="200" /> | <img src="assets/screenshots/vehiculeV2.PNG" width="200" /> | <img src="assets/screenshots/splashV2.PNG" width="200" /> |

---

### 🕰️ Ancienne Version (2023)
*La base historique du projet Wasselni.*

| Recherche V1 | Résultats V1 | Détails Recherche V1 |
|:---:|:---:|:---:|
| <img src="assets/screenshots/rechercheV1.jpg" width="180" /> | <img src="assets/screenshots/resultatRechercheV1.jpg" width="180" /> | <img src="assets/screenshots/detailsRechercheV1.jpg" width="180" /> |

| Profil V1 | Inscription V1 | Connexion V1 |
|:---:|:---:|:---:|
| <img src="assets/screenshots/ProfilV1.jpg" width="180" /> | <img src="assets/screenshots/inscriptionV1.jpg" width="180" /> | <img src="assets/screenshots/connexionV1.jpg" width="180" /> |

| Mes Annonces V1 | Publier V1 | Véhicule V1 |
|:---:|:---:|:---:|
| <img src="assets/screenshots/mesAnnoncesV1.jpg" width="180" /> | <img src="assets/screenshots/publierV1.jpg" width="180" /> | <img src="assets/screenshots/vehiculeV1.jpg" width="180" /> |

| Notifications V1 | Mot de passe V1 | Infos V1 |
|:---:|:---:|:---:|
| <img src="assets/screenshots/notifV1.jpg" width="180" /> | <img src="assets/screenshots/mdpV1.jpg" width="180" /> | <img src="assets/screenshots/infoV1.jpg" width="180" /> |



---
## 🧠 Défis Techniques & Apprentissages

Le passage de la V1 (2023) à la V2 (2026) a permis de relever plusieurs défis majeurs :

* **Migration vers TypeScript :** Sécurisation de l'ensemble de la base de code pour réduire les erreurs au runtime et améliorer l'autocomplétion.
* **Gestion d'état complexe :** Mise en place de **Redux Toolkit** pour synchroniser les données de l'utilisateur, les trajets disponibles et les notifications en temps réel.
* **Performance UI :** Utilisation de `FlashList` ou `FlatList` optimisées pour l'affichage de nombreux trajets sans ralentissement.
* **Temps Réel avec Firebase :** Implémentation de listeners pour mettre à jour instantanément les réservations et les annonces.

---
## 🗺️ Roadmap & Évolutions Futures

Wasselni continue d'évoluer. Voici les prochaines fonctionnalités prévues :
* [ ] **Système de Paiement :** Intégration d'une passerelle de paiement sécurisée (Stripe ou API locale).
* [ ] **Chat en temps réel :** Messagerie interne entre conducteur et passager via Firebase Cloud Messaging.
* [ ] **Géolocalisation Live :** Suivi en temps réel du véhicule sur la carte pendant le trajet.
* [ ] **Vérification d'identité :** Système de badge "Vérifié" avec scan de pièce d'identité.

---

## ⚙️ Installation (Développement)

> **Note :** Ce dépôt est une vitrine. Si vous avez accès au code source, voici comment le lancer :

1.  **Cloner le projet :** `git clone ...`
2.  **Installer les dépendances :** `npm install`
3.  **Configurer Firebase :** Ajouter votre fichier `firebase.js` à la racine.
4.  **Lancer l'application :** `npx expo start`

---
---
---

## 🏁 Conclusion & Crédits

Ce projet est l'aboutissement d'un travail d'équipe réalisé dans le cadre d'un **projet de Licence en 2023**. L'évolution vers la version actuelle (2026) a été portée par une volonté constante d'amélioration technique et d'optimisation de l'expérience utilisateur.

**L'équipe de développement (2023) :**
* 👨‍💻 **LAFENDI Abdallah Imad**
* 👨‍💻 **CHOUKCHOU BRAHAM Youssouf**
* 👩‍💻 **MERAD Ghita**
* 👩‍💻 **MERAD Rania**

---

## ⚖️ Licence & Copyright

Copyright © 2023-2026 **LAFENDI Abdallah Imad** & Co-auteurs. Tous droits réservés.

Le code source de cette application est **privé**. Toute reproduction, modification ou distribution non autorisée de ce code, de l'architecture du projet ou des ressources graphiques (logo, interfaces) est strictement interdite sans l'accord préalable des auteurs.

---

**Contactez-moi pour toute demande de collaboration ou de démonstration :**
📧 [lafendiabdallahimad@gmail.com]  
🔗 [https://www.linkedin.com/in/abdallah-imad-lafendi-476803326/]
