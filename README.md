# homepage
A simple static homepage for my server

## running the docker container
sudo docker build -t webserver-image:v1 .
sudo docker run -d -p 80:80 webserver-image:v1
