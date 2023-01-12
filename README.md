# DockerIsation

## Dockeriser le front et le back :

Dans un terminal se placer dans le dossier ECF-cda-backEnd,
Lancer la commande :

```
docker-compose build
```

Se déplacer sur le dossier racine "DockerFrontBack",
Lancer la commande :

```
docker compose up
```

---

### Commandes déjà effectués :

Dans le terminal, dans le dossier ./ECF-cda-backEnd ( pour un projet gradle ),
si jamais des modifications sont effectués sur l'application Spring

```
./gradlew clean build
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

est prévue pour fonctionné uniquement avec le profil dev, avec le build actuel et la dockerisation celle-ci ne sera pas acessible.

---

## FrontEnd Data :

Ajouter des data avec postman, pour l'affichage sur le front
( liaison avec entre le back et le front incomplêtes, toutes les fonctionnalités ne sont pas fonctionnelles, mais affichage / suppréssion / edition partielle des clients et véhicules fonctionnne. )
.
