# docker-httpfolder

## Build

```sh
docker build -t httpfolder .
```

## Run

```sh
docker run -d -p 80:8080 -e USERNAME=user -e PASSWORD=pass -v `pwd`/data:/www-data httpfolder
```

