# HookMastery: Unleashing the Power of Hooks

Une application Next.js de génération d'images IA qui démontre l'utilisation des hooks React et les meilleures pratiques de développement.

## Description du Projet

Ce projet est une application web basée sur Next.js qui permet aux utilisateurs de générer des images alimentées par l'IA en fournissant des prompts textuels. L'application s'interface avec l'API GPT-4 Image Generation pour créer des images uniques basées sur les entrées utilisateur.

## Objectifs d'Apprentissage

En complétant ce projet, vous allez :

- Comprendre et implémenter la gestion d'état React avec useState
- Créer et utiliser des hooks React personnalisés
- Travailler avec les variables d'environnement pour la gestion des clés API
- Implémenter des routes API dans les applications Next.js
- Développer des composants React réutilisables
- Gérer l'état de l'application à travers plusieurs composants
- Implémenter un design UI responsive avec Tailwind CSS
- Gérer les opérations asynchrones en React
- Suivre les meilleures pratiques React pour la structure et l'organisation des composants

## Structure du Projet

Le projet évolue à travers plusieurs versions (0x07 à 0x13), chaque version ajoutant de nouvelles fonctionnalités :

### alx-project-0x07 - Configuration de base
- Layout et composants de base
- Structure de fichiers Next.js
- Configuration TypeScript et Tailwind CSS

### alx-project-0x08 - Gestion d'état
- Implémentation de useState
- Composant ImageCard
- Gestion d'état basique

### alx-project-0x09 - Environnement local
- Configuration des variables d'environnement
- Fichier .env.local
- Gestion sécurisée des clés API

### alx-project-0x10 - Intégration API
- Route API pour la génération d'images
- Appels fetch vers l'API GPT-4
- Gestion des erreurs

### alx-project-0x11 - Suivi des images
- Historique des images générées
- Galerie d'images
- État de l'application étendu

### alx-project-0x12 & 0x13 - Hook personnalisé
- Hook useFetchData réutilisable
- Logique de récupération de données abstraite
- Architecture de composants améliorée

## Prérequis

- Node.js (v14 ou plus récent)
- Next.js (v13 ou plus récent)
- React (v18 ou plus récent)
- TypeScript
- Tailwind CSS
- Clé API GPT-4 (de RapidAPI)
- Navigateur web moderne

## Installation et Utilisation

1. Naviguer vers le répertoire du projet souhaité :
   ```bash
   cd alx-project-0x07  # ou toute autre version
   ```

2. Installer les dépendances :
   ```bash
   npm install
   ```

3. Configurer les variables d'environnement (pour 0x09 et versions ultérieures) :
   - Créer un fichier `.env.local`
   - Ajouter votre clé API : `NEXT_PUBLIC_GPT_API_KEY="VOTRE_CLE_API"`

4. Lancer le serveur de développement :
   ```bash
   npm run dev -- -p 3000
   ```

5. Ouvrir votre navigateur à `http://localhost:3000`

## Fonctionnalités Clés

### Génération d'Images
- Entrée de prompt textuel
- Intégration API avec GPT-4 Image Generation
- États de chargement pendant la génération

### Galerie d'Images
- Historique des images générées
- Aperçus en miniatures
- Clic pour voir l'image complète

### Interface Utilisateur Responsive
- Fonctionne sur mobile et desktop
- Design moderne et propre
- Navigation intuitive

### Hooks Personnalisés
- Logique de récupération de données réutilisable
- Abstraction de la gestion d'état
- Gestion des erreurs

## Meilleures Pratiques Implémentées

- **Organisation des Composants** : Séparation logique des composants de layout et fonctionnels
- **Gestion d'État** : Utilisation appropriée des hooks React
- **Gestion des API** : Route API côté serveur pour l'utilisation sécurisée des clés API
- **Sécurité** : Clés API stockées dans les variables d'environnement
- **UI/UX** : Design responsive avec Tailwind CSS
- **Sécurité de Type** : Interfaces TypeScript pour tous les composants et props

## Notes de Développement

Chaque version du projet démontre des concepts progressivement plus avancés, permettant un apprentissage étape par étape des hooks React et des meilleures pratiques de développement.

Pour un usage en production, des fonctionnalités supplémentaires pourraient inclure :
- Authentification utilisateur
- Stockage persistant des images générées
- Gestion d'erreurs plus avancée
- Capacités d'édition d'images
- Fonctionnalités de partage social
