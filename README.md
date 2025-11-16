🚀 TODO-App: Priorisez et Organisez vos Tâches
Une application simple et efficace, conçue pour vous aider à classer vos tâches quotidiennes en fonction de leur niveau d'importance (Urgent, Moyen, Bas) et à gérer votre productivité.

💻 Technologies Utilisées
Ce projet est construit sur une stack moderne, légère et performante, garantissant une excellente expérience de développement et une interface utilisateur soignée.

Frontend Framework : React (avec Hooks)

Langage : TypeScript (pour un code robuste et typé)

Bundler & Tooling : Vite

Styling & UI : Tailwind CSS

Composants UI : DaisyUI (en utilisant le thème night)

Icônes : Lucide-React

✨ Fonctionnalités (Features)
L'application TODO-App propose les fonctionnalités suivantes, centrées sur la gestion des priorités :

Gestion des Priorités : Chaque tâche peut être assignée à l'un des trois niveaux : Urgente, Moyenne, ou Basse.

Ajout de Tâches : Ajouter de nouvelles tâches via un champ de saisie simple.

Filtrage par Priorité : Afficher uniquement les tâches correspondant à une priorité spécifique ("Tous," "Urgent," "Moyen," ou "Basse").

Marquage & Suppression par Sélection : Les tâches peuvent être sélectionnées via une case à cocher, permettant de les marquer comme terminées en groupe ou de les supprimer individuellement.

Persistance des Données : La liste des tâches est automatiquement sauvegardée dans le Local Storage du navigateur.

Interface Réactive : L'interface utilise une mise en page flexible pour s'adapter à différentes tailles d'écran (mobile-friendly).

🛠️ Processus de Création
Ce projet a été construit en se concentrant sur une architecture claire et une interface utilisateur agréable, en s'appuyant sur des outils modernes :

Initialisation avec Vite et TypeScript : Utilisation du template React + TypeScript de Vite pour un démarrage rapide et l'exploitation des avantages du typage statique.

Choix de Tailwind CSS et DaisyUI : Intégration de Tailwind CSS pour un développement rapide de l'interface (vite.config.ts), complété par DaisyUI pour fournir des composants UI stylisés, en particulier le thème night pour un look sombre et moderne.

Implémentation de la Logique de Priorité : La fonctionnalité clé repose sur la structure de données Todo (dans App.tsx et TodoItem.tsx) qui inclut un champ priority de type "Urgente" | "Moyenne" | "Basse".

Gestion de l'État : L'état global des tâches (todos), de l'entrée utilisateur (input), de la priorité sélectionnée (priority) et de la sélection des tâches à terminer (selectedTodos) est géré par des useState et des useEffect pour la persistance locale.

⚙️ Démarrer le Projet Localement
Suivez ces instructions pour mettre en place et lancer l'application sur votre machine de développement.

Prérequis
Vous devez avoir installé :

Node.js (recommandé v18+)

npm (ou un autre gestionnaire de paquets comme yarn ou pnpm)

1. Clonage du Répertoire
Ouvrez votre terminal et exécutez la commande pour récupérer le code :

Bash

git clone https://github.com/s-loretta/todoapp-react
cd todoapp-react
2. Installation des Dépendances
Installez toutes les dépendances du projet :

Bash

npm install
# ou
yarn install
3. Lancement du Serveur de Développement
Démarrez l'application en mode développement. Elle bénéficiera du Hot Module Replacement (HMR) grâce à Vite :

Bash

npm run dev
# ou
yarn dev
L'application sera accessible dans votre navigateur, généralement à l'adresse suivante : http://localhost:5173/.
