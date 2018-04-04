# Mysql + PhpMyAdmin with docker

1. Set variables in docker-compose.yml

2. Start services
```
docker-compose up -d
```

3. Persistent storage
Mysql data are stored in ```storage/``` folder, so you can restore containers from scratch without losing anything
```
docker-compose stop && docker-compose rm -f && docker-compose up -d
```
