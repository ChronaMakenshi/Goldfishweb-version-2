# Goldfishweb

Bienvenue dans le projet **Goldfishweb** ! Goldfishweb est une plateforme de freelancing qui utilise les technologies modernes pour offrir une expérience utilisateur fluide et dynamique. Ce README fournit des informations essentielles pour comprendre, configurer et contribuer au projet.

## Structure du Projet

Le projet est divisé en deux principales sections : **Back-end** et **Front-end**.

### 1. Dossier Back-end (PHP)

Le dossier `back-end` contient le code source du serveur, écrit en PHP. Ce code gère la logique métier, les bases de données et l'API qui communique avec le front-end.

#### Installation

1. **Clonez le dépôt** :
   ```
   git clone https://github.com/your-username/goldfishweb.git
   ```
#### Accédez au dossier back-end :

```
cd goldfishweb/back-end
```

Installez les dépendances PHP : Assurez-vous que Composer est installé. Puis, exécutez :

```
composer install
```
Configurez l'environnement : Renommez .env.example en .env et configurez les paramètres en fonction de votre environnement.

#### Initialisez la base de données :
```
php artisan migrate
```
Démarrez le serveur :
```
php -S localhost:8000 -t public
```

2. Dossier Front-end (Vue.js)
Le dossier front-end contient le code source du client, développé en Vue.js et utilisant Less pour les styles.

#### Installation
Accédez au dossier front-end :
```
cd goldfishweb/front-end
```

Installez les dépendances : Assurez-vous que Node.js et npm sont installés. Puis, exécutez :
```
npm install
```
Démarrez le serveur de développement :
```
npm run serve
Construisez pour la production :
```
```
npm run build
Développement
```
Pour contribuer au projet :

Faites une branche pour votre fonctionnalité :
```
git checkout -b ma-fonctionnalite
```
Effectuez vos modifications et testez-les localement.

#### Committez vos modifications :

```
git add .
git commit -m "Ajout de [fonctionnalité/bugfix]"
```

Poussez votre branche et ouvrez une pull request :

```
git push origin ma-fonctionnalite
```
