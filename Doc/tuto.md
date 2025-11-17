Outils à comparer :

SonarCloud (SAST)

SonarQube local (SAST)

Snyk (SCA)

Dependabot (SCA)

PHPStan (Analyse PHP)

ESLint (Analyse JS)

GitHub CodeQL (SAST)



# pm2etml-apps:
 ## Prérequis
* PHP 8.1
* Composer
 * PNPM

OU

## Docker 
(avec sail, voir docker-compose.yml)

## Dépendances PHP
-> Si nécessaire, installer composer (et PHP 8.1 par la même occasion)
```sh
composer install
```
## Dépendances Javascript
Si nécessaire, installer NPM
``` 
pnpm install
``` 
Fichier de configuration  
```
cp .env.example .env
php artisan key:generate --ansi
```

Adapter si nécessaire la configuration (fichier .env) avec la base de données utilisée