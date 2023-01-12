# DockerIsation

## Dockeriser le front et le back :

Dans un terminal se déplacer sur le dossier racine "DockerFrontBack"

Et lancer la commande :

```
docker compose up
```

---

### Commandes déjà effectués :

Dans le terminal, dans le dossier ./ECF-cda-backEnd ( pour un projet gradle )

```
./gradlew clean build
```

puis

```
docker-compose build
```

---

## POSTMAN

Importer le ficher
"ECF-Localib-backend.postman_collection.json"
Dans postman

la request :

```
http://localhost:8080/debug/init
```

Permet de rajouter des données à la DB pour tests si besoins
