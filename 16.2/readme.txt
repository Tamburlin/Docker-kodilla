use 
docker build -t apache-docker-example -f ./Dockerfile.txt .
and
docker run -d --name httpd-docker-01 -p 192.168.99.100:8080:80 apache-docker-example