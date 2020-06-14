# homepage
A simple static homepage for my server

## running the docker container
rough instructions for using the Dockerfile in this repo:
```Bash
sudo docker build -t homepage:v1 .
sudo docker run -d -p 80:80 webserver-image:v1
```
and then go to `localhost` or `localhost:80` in your web browser to have a look
