# XinDocker

docker run --name mysql \  
-v /data/db/mysql/data:/var/lib/mysql \  
-v /data/db/mysql/conf.d:/etc/mysql/conf.d \  
-e MYSQL_ROOT_PASSWORD=Kerui0613 \  
-d mysql:5.6
