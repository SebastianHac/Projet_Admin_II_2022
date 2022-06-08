# Admin 2

Projet dans le cadre du cours d'admin 2 à l'Ephec

## Commande utile pour docker :

* Créer une image docker : docker build -t [nom de l'image voulue]
* Créer un container docker : docker run -tid -p [container-port]:[host-machine-port] --name [container-name] [image-name]
* Executer des commande dans un container docker : docker exec -it [container-name] bash
* Afficher les images docker : docker image ls
* Afficher les containers docker : docker container ls
* Supprimer toutes les images : docker system prune -a --volumes
