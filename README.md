# Sprawozdanie_1_Lab4
docker build -f DockerFile -t ghcr.io/pielakm/web100 .
docker run -d --name sprawko -p 8080:80 ghcr.io/pielakm/web100:latest
docker images
