# Docker-HelloWorld-1MB

Dockerfile: create a 1MB size with single layer



## How to generate random 1MB file?

```shell
dd if=/dev/random of=output.file bs=1024 count=1024
```



## How to build docker images?

```shell
docker build -t="helloworld:1MB" .
```
