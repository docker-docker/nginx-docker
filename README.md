# nginx-docker

A slim base version image for nginx

# How to use this `Dockerfile`

```shell

$ docker build -f Dockerfile -t test:nginx .
$ docker run --name test -d -p 80:80 -v $PWD:/opt/app test:nginx

```