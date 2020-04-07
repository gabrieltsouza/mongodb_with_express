# mongodb_with_express
Docker compose for ecommerce project. MONGODB / MONGOEXPRESS / DOCKER


pre requirements:
Docker / Docker compose / Docker Desktop installed

Database files configured to store in -> D:\FilesEcommerceProj\Database\mongodb_with_express\data

To up the database:
docker-compose up -d

To check virtual network:
docker network ls

To check the containers:
docker-compose ps

To down the database:
docker-compose down


To check the logs if container exited:
docker logs -t mongodb_with_express_mongo_1