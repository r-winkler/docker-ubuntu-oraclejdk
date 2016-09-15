# Ubuntu and Oracle JDK 

This is a docker container based on Ubuntu with Oracle JDK installed.


## Installation

```
docker pull renewinkler/ubuntu-oraclejdk
```

## Build

```
docker build . -t ubuntu-oraclejdk
```


## Launch

```
docker run -itd --name ubuntu renewinkler/ubuntu-oraclejdk
```


## Connect to Server

```
docker exec -it ubuntu /bin/bash
```
