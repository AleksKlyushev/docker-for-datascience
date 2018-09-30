sudo docker run -v /home/aleksandr/docker/:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:2c80cf3537ca
16f01177

sudo docker build -t my_notebook /home/aleksandr/docker
sudo docker run -v /home/aleksandr/docker/:/home/jovyan/ -p 8888:8888 my_notebook

sudo docker exec -it e98016c4d184 bash

docker cp wine.data e98016c4d184:/home/jovyan/wine.data 

docker-compose up
