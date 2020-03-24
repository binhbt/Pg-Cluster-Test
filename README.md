# Pg-Cluster-Test
Pg-Cluster-Test
docker swarm init --advertise-addr=IP  
docker node update --label-add type=primary hostname  
docker stack deploy --compose-file=./docker-compose.yml pg-stack   

