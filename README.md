# docker-compose
a l'intérieur de docker-compose.yml, il y a deux chose a modifier.

{path} (L 13 / 29 / 45) qui correspond au chemin ou vas être stocker les agent.
{name} (L 16 / 32 / 48). qui sera le nom de votre agent.

```
pour la commande :
docker-compose -f Path/To/docker-compose.yml up -d

```
## Mise à jour:

````
docker pull testproject/agent

````

Redemarez les docker, et tout est ok. 
