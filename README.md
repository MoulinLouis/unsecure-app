# Unsecure Project

## Correctif groupe 6 / 3IW3

Fork de ```https://github.com/LouisHrg/unsecure-app```
 
Comprends l'ensemble des correctifs effectuées par le groupe 6 de la classe 3IW3

## Pour lancer le projet


1. Clonez le repo
2. Buildez le docker : ```docker-compose build```
3. Lancez le docker : ```docker-compose up```
4. Copiez le .env.example et renommez le .env
5. Lancez ```composer install```
4. Lancez la commande ```docker-compose exec php php artisan key:generate```
5. Lancez la commande ```docker-compose exec php php artisan storage:link```
6. Lancez la commande pour créer les tables : ```docker-compose exec php php artisan migrate```
7. Lancez la commande pour ajouter des données de test : ```docker-compose exec php php artisan db:seed```
8. Le site est accessible sur ```localhost```

**Pour lancer des commmandes laravel vous pouvez faire ```docker-compose exec php php artisan votre:commande```

Vous pouvez accéder à adminer sur ```localhost:8080```

