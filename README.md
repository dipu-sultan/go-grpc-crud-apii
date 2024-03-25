# go-grpc-crud-apii
Building a CRUD gRPC API using Postgresql DB in GO

in terminal

$ sudo docker run -d -e "POSTGRES_USER=root" -e "POSTGRES_PASSWORD=123456" -e "POSTGRES_DB=test_db" -p 54321:5432 --name postgres --mount "type=volume,source=postgres,destination=/var/lib/postgresql/data" postgres

go to your project in vs code run: $ go run server/main.go
open another terminal: $ go run client/main.go
