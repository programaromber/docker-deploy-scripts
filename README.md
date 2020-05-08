#echo "# docker-deploy-scripts" >> README.md
#COMANDOS


docker stack deploy -c D:\kdi\docker\deploy-scripts\postgres-stack.yml postgres

docker stack deploy -c D:\kdi\docker\deploy-scripts\keycloak-stack.yml keycloak
