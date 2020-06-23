# docker-first-project
#link for docker image- https://hub.docker.com/r/riajasm/firstapp

#steps to dockerize

#first create image
sudo docker build -t myform .
sudo docker images
sudo docker run -it -p 8080:8081 myfirstapp

#put image on docker hub
docker login --username=use_your_own --password=use_your_own
sudo docker tag 7797f0630cd4 riajasm/myfirstapp:hello
sudo docker push riajasm/myfirstapp
sudo docker push riajasm/myfirstapp:hello
