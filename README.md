# hadoop-python

## Install local Hadoop cluster

```
git clone https://github.com/big-data-europe/docker-hadoop
cp docker-compose.yml docker-hadoop
cd docker-hadoop
sudo docker-compose up -d
docker container ls # смотрим контейнеры
```
![image](https://raw.githubusercontent.com/cr00z/hadoop-python/main/images/hadoop.jpg)
```
# sudo chown $USER /var/run/docker.sock # если не будет прав
docker exec -it namenode /bin/bash
```

The current status of the local Hadoop cluster http://localhost:9870

