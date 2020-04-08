# mongodb_with_express
Docker compose for ecommerce project. MONGODB / MONGOEXPRESS / DOCKER

#Pre requirements:
Docker / Docker compose / Docker Desktop installed

#Database files configured to store inside a virtual volume

#To up the database containers:
docker-compose up -d

#To check virtual network:
docker network ls

#To check the containers:
docker-compose ps
docker container ps
docker stats

#To stop and remove the database container:
docker-compose down

#To stop the database container:
docker-compose stop

#To check the logs if container exited:
docker logs -t mongodb_with_express_mongo_1

#To list volumes
docker volume ls
inspect volume
docker volume inspect mongodb_with_express_volume_mongo_database_files

#To remove volume
docker volume rm mongodb_with_express_volume_mongo_database_files

#Logs do container
docker logs -f mongodb_with_express_mongo_1
docker logs -f mongodb_with_express_mongo-express_1

#Shell inside container
docker container exec -it mongodb_with_express_mongo_1 bash