# 🚀 TODO-App: Priorisez et Organisez vos Tâches

> **Une application minimaliste et réactive, conçue pour vous aider à classer vos tâches quotidiennes en fonction de leur niveau d'importance (Urgent, Moyen, Bas) et à gérer votre productivité.**

---

## 💻 Technologies Utilisées

Ce projet est construit sur une stack moderne, légère et performante, garantissant une excellente expérience de développement et une interface utilisateur soignée.

* **Frontend Framework** : **React** (avec Hooks)
* **Langage** : **TypeScript** (pour un code robuste et typé)
* **Bundler & Tooling** : **Vite**
* **Styling & UI** : **Tailwind CSS**
* **Composants UI** : **DaisyUI** (en utilisant le thème `night`)
* **Icônes** : **Lucide-React**

---

## ✨ Fonctionnalités (Features)

L'application `TODO-App` offre une expérience utilisateur fluide, centrée sur la gestion des priorités et la persistance des données :

* **Gestion des Priorités** : Chaque tâche peut être assignée à l'un des trois niveaux : **Urgente**, **Moyenne**, ou **Basse**.
* **Ajout de Tâches** : Ajouter de nouvelles tâches via un champ de saisie simple.
* **Filtrage Dynamique** : Visualiser les tâches filtrées par priorité ou afficher la liste complète (Tous). Les compteurs sont affichés pour chaque catégorie (Urgent, Moyen, Basse).
* **Persistance des Données** : La liste des tâches est automatiquement sauvegardée dans le **Local Storage** du navigateur.
* **Marquage & Suppression par Sélection** : Les tâches peuvent être sélectionnées via une case à cocher. Un bouton permet de supprimer toutes les tâches sélectionnées en une seule action.
* **Interface Utilisateur** : L'application utilise le thème **Night** de DaisyUI pour un design sombre et le style `gradient-text` personnalisé pour le titre.

---

## 🛠️ Processus de Création

Le développement a été guidé par les principes de la modernité et de la clarté du code :

1.  **Fondations Modernes** : Le projet a été initialisé avec **Vite** et **TypeScript** pour bénéficier d'une vitesse de développement optimale et d'un code fortement typé.
2.  **Architecture et Style** : Utilisation du composant fonctionnel `App.tsx` comme conteneur principal et d'un composant dédié `TodoItem.tsx` pour chaque élément, favorisant la réutilisabilité.
3.  **Intégration du Style** : **Tailwind CSS** et **DaisyUI** ont été intégrés (`vite.config.ts`, `index.css`) pour accélérer la conception de l'interface en se concentrant sur les classes utilitaires.
4.  **Logique Métier Avancée** : Le système d'état inclut la gestion de la priorité, du filtre actif, et d'un `Set` pour la sélection multiple des tâches, simplifiant l'action de "Finir la sélection".

---

## ⚙️ Démarrer le Projet Localement

Suivez ces instructions pour cloner et exécuter l'application sur votre machine.

### Prérequis

Assurez-vous que les logiciels suivants sont installés sur votre système :

* **Node.js** (recommandé v18+)
* **Git**

### 1. Clonage du Répertoire

Ouvrez votre terminal et clonez le dépôt :

```bash
git clone [https://github.com/s-loretta/todoapp-react](https://github.com/s-loretta/todoapp-react)
cd todoapp-react
2. Installation des Dépendances
Installez tous les modules nécessaires listés dans package.json :

Bash

npm install
# ou
yarn install
3. Lancement du Projet
Démarrez l'application en mode développement en utilisant le script dev :

Bash

npm run dev
# ou
yarn dev
L'application sera lancée par Vite et accessible dans votre navigateur, généralement à l'adresse http://localhost:5173/.
