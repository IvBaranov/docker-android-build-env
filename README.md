# docker-android-build-env

## Sample usage
```
docker run -ti -v /your/out/path:/var/local/out --name some-android-build-env ivbaranov/android-build-env
```

## ... via `docker-compose`
```
version: "2"

services:
    builder:
        image: ivbaranov/android-build-env
        restart: always
        container_name: android-build-env
        volumes:
            - /your/out/path:/var/local/out
```
