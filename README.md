# nextJS-documentation

# Introduction
## Pourquoi ce document ?
Combien d'entre  vous qui a consacre une qantite de temps considerable pour apprendre une competence pratique comme le web developement , resoudre des problemes courant , faire des recherches incessante pour vous ameliorer chaque jour mais d'un jour ou lendemain vous rencontrez le meme probleme que vous avez resolu deux ans de cela par exemple, ou encore vous avez un peu vous eloignez du domaine pendant un certain periode et apres quelque temps vous decidez de reprendre vos armes et c'est alors que vous constater que tu dois tout reprendre. Bien sur il se peut tu ne reprends pas tout mais ce serait beaucoup plus simple si tu avais documenter ton apprentissage et les differents probleme courant que tu avais resolus. En effet c'est cette experience qui m'a convaincu de documenter tous mes apprentissages et les etapes de solution de chaque probleme pertinent que j'ai pu resoudre.

## Ce que ce document n'est pas 
Ce document n'est aucun cas un documentation complete du framework NextJS mais de preference une partage de contenu qui peut bien aider quelqu'un d'autre .Il vise surtout a vous fournir les bases cles pour debuter NextJS.

## Prerequis 
Pour commencer avec Next.js, voici quelques prérequis que vous devez avoir :

1. **Connaissance de base en JavaScript** : Comprendre les fondamentaux de JavaScript est essentiel pour travailler avec Next.js, car c'est un framework JavaScript basé sur React.

2. **Compréhension de React** : Next.js étant construit sur React, une bonne compréhension de React est nécessaire. Assurez-vous de connaître les concepts de base de React tels que les composants, le JSX, les états et les props.

3. **Node.js et npm (ou yarn)** : Next.js utilise Node.js pour l'exécution côté serveur et npm (ou yarn) pour la gestion des dépendances. Assurez-vous d'avoir Node.js installé sur votre machine avec npm ou yarn.

4. **Éditeur de texte ou IDE** : Choisissez un éditeur de texte ou un environnement de développement intégré (IDE) pour écrire du code. Des options populaires incluent Visual Studio Code, Sublime Text, Atom, etc.

5. **Terminal** : Vous aurez besoin d'un terminal pour exécuter des commandes et interagir avec votre projet Next.js. Assurez-vous d'être à l'aise avec l'utilisation du terminal.


## NextJS , c'est quoi ?
Next.js est un framework JavaScript open source qui permet de construire des applications web modernes et évolutives en utilisant React. Il offre une structure de projet prête à l'emploi avec un routage intégré, un rendu côté serveur, le support des données pré-rendues et un déploiement simple.

# Installer nextJS

Pour installer Next.js, vous devez suivre quelques étapes simples. Voici comment procéder :

### Étapes d'installation :

1. **Créer un nouveau projet** : Ouvrez votre terminal et créez un nouveau répertoire pour votre projet Next.js.

   ```bash
   mkdir mon-projet-nextjs
   cd mon-projet-nextjs
   ```

2. **Initialiser un nouveau projet Node.js** : Utilisez npm ou yarn pour initialiser un nouveau projet Node.js. Assurez-vous d'avoir Node.js installé sur votre machine.

   ```bash
   npm init -y
   # ou
   yarn init -y
   ```

3. **Installer Next.js** : Utilisez npm ou yarn pour installer Next.js en tant que dépendance de développement dans votre projet.

   Avec npm :

   ```bash
   npm install next react react-dom
   ```

   Avec yarn :

   ```bash
   yarn add next react react-dom
   ```

4. **Ajouter des scripts au package.json** : Modifiez votre fichier `package.json` pour ajouter des scripts qui vous permettront de démarrer et de construire votre application Next.js.

   ```json
   "scripts": {
       "dev": "next dev",
       "build": "next build",
       "start": "next start"
   }
   ```

### Exécuter votre application Next.js :

- **Mode développement** : Pour exécuter votre application en mode développement, utilisez la commande `npm run dev` ou `yarn dev`. Cela démarrera un serveur de développement local.

   ```bash
   npm run dev
   # ou
   yarn dev
   ```

- **Mode production** : Une fois que vous êtes prêt à déployer votre application, utilisez la commande `npm run build` ou `yarn build` pour construire votre application, puis `npm start` ou `yarn start` pour démarrer le serveur en mode production.

   ```bash
   npm run build
   npm start
   # ou
   yarn build
   yarn start
   ```

Maintenant, votre application Next.js est prête à être développée et déployée ! Assurez-vous de consulter la documentation officielle de Next.js pour en savoir plus sur les fonctionnalités et les bonnes pratiques de développement.

