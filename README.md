--please run this for docker image and container
docker pull postgres
docker run --name CoreWebAPI -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -p 5432:5432 postgres
docker container start CoreWebAPI
