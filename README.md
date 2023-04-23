# Projet de base de donnée

L'objectif est de mettre à disponisition une base de données sous Postgres SQL avec des données. La base de donnée génère automatique ces données.

Les étapes pour la mise en place

```bash
# copie le projet en local
git clone http://formation.git

# Lancez la base de donnée
docker-compose --project-name liveaddict_bdd  up -d --remove-orphans
```

Le projet contient une base de donnée ainsi que le client web pgadminc accéssible depuis l'adresse http://localhost:5433/ (login : admin@formation.com, password : pass49)
