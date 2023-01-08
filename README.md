# MasterDPT

Docker commands:

docker run -e POSTGRES_PASSWORD=postgrespassword -p 5432:5432 -d postgres
docker exec -it bash; name of the container: "docker container ps"
psql -h localhost -U postgres
\l => displays the existing databases
\c postgres => Connect to database "postgres
\dt => indicates that there are no tables
start the Java application
\dt now shows the created database tables
