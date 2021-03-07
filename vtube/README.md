# vtube
Interface Utilisateur de l'application vtube

## Prérequisites
* nodejs doit être installé
* Docker doit être installé
  
## Démarrer l'application localement
`npm run start:dev`
## Dockerisation
### Creation de l'image Docker
`docker build -t vtube:RELEASE-0.0.1 --file Dockerfile .`
### Lister les images
`docker image list`
### Démarrage du conteneur docker
`docker run -d -p 3000:3000 vtube:RELEASE-0.0.1`

