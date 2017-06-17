#Build docker image yzhang/ubuntu with following command.

```
docker-compose build
```

#Start the container with following command.

```
docker run -v C:\YOUR\LOCAL\PATH\tmp:/tmp -it yzhang/ubuntu
```
##For Example
```
docker run -v D:\workspace:/tmp -it yzhang/ubuntu
```
