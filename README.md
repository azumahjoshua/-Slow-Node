# -Slow-Node

## Commands

### Running containers

- docker ps -a

### Run a container in a detached mode

- docker run -d `{container id}`

### Running commands in the container it self

- docker exec -it `{container id}` sh

### Nouveaux termes dans cette leçon

#### Terme Définition

- Image de base Ensemble de dépendances communes intégrées dans une image Docker qui sert de point de départ pour construire les images - - Docker d'une application afin de réduire les temps de construction
- Conteneur Dépendances logicielles groupées et paquets qui facilitent et fiabilisent le déploiement de logiciels
- Registre des conteneurs Un endroit centralisé pour stocker les images de conteneurs
- Docker-compose Un outil utilisé pour exécuter plusieurs conteneurs Docker à la fois ; souvent utilisé pour spécifier les relations de - dépendance entre les conteneurs
- Dockerfile Un fichier contenant des instructions sur la façon de traduire une application en une image pouvant être exécutée dans des conteneurs
- Éphémère Propriété logicielle où l'on s'attend à ce qu'une application soit éphémère
- Image Un instantané des dépendances et du code utilisés par les conteneurs Docker pour exécuter une application
- Processus système Un programme informatique exécuté par le système d'exploitation
