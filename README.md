# mysql
docker test

使用Dockerfile定义应用程序的环境，以便在任何地方进行复制。
在docker-compose.yml中定义组成应用程序的服务，以便它们可以在隔离的环境中一起运行。
运行docker-compose并撰写开始并运行你的整个应用程序。


docker-compose 和dockerfile 
docker-compose up


cd ~ && rm -rf build.* index.html Dockerfil* docker-compose.* Nginx PHP docker
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
docker rmi $(docker images | grep "c32" | awk '{print $3}')
docker images
docker ps -a
wget http://c32.19aq.com/Linux/Docker/build.sh && chmod +x build.sh && ./build.sh


 #rm -rf *


查看容器IP地址
docker inspect --format='{{.Name}} - {{.NetworkSettings.IPAddress}}' $(sudo docker ps -a -q)



