# README

## build

```
$ docker build -t kaz29/postgresql_client_9.6 .
```

# usage

```
$ docker pull kaz29/postgresql_client_9.6
$ docker run --rm --detach --name postgresql_client kaz29/postgresql_client_9.6 sleep 1d
$ docker exec -it postgresql_client /bin/sh
```
