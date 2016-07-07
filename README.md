# docker-cov-hygui
COV Hygieia UI Image for Open DevOps Pipeline

#docker pull
docker pull devopsopen/docker-cov-hygui

#docker run : 
docker run -t -p 8088:80 --link hyapi --name hygui -i devopsopen/docker-cov-hygui

Preparement: container hyapi should be started with the ame of hyapi in advance.
