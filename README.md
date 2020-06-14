# homepage
A simple static homepage for my server

## running the docker container
rough instructions for using the Dockerfile in this repo:
```Bash
# build and run the image
sudo docker build -t homepage:1 .
sudo docker run -d -p 80:80 homepage:1
```
and then go to `localhost` or `localhost:80` in your web browser to have a look.

when you're done, you can stop and remove the container:
```Bash
sudo docker ps -a
# copy the container id from the output of the above command
sudo docker stop [container-id]
sudo docker rm [container-id]
```
and now you should be back to a clean slate
