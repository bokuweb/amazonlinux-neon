# amazonlinux-neon

An AmazonLinux with NEON(Rust + Node) docker container

It's on [docker-hub](https://hub.docker.com/r/bokuweb/amazonlinux-neon/) and [github](https://github.com/bokuweb/amazonlinux-neon/)

## tags and links
* `latest` [(master/Dockerfile)](https://github.com/bokuweb/amazonlinux-neon/blob/master/Dockerfile)


## how to build

```sh
git clone git@github.com:bokuweb/amazonlinux-neon.git
cd amazonlinux-neon
docker build --rm -t bokuweb/amazonlinux-neon .
```

## running

```sh
docker run --rm  -it bokuweb/amazonlinux-neon
```
