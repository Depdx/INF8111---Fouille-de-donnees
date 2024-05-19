# INF8111---Fouille-de-donnees


## Start Colabl container

```bash
docker run --gpus=all --cpuset-cpus="0-31" -p 127.0.0.1:9000:8080 us-docker.pkg.dev/colab-images/public/runtime
```


## Copy files from content 

### Find container ID
```bash
docker ps
```

### Copy files

```bash
docker cp <Container ID>:/content/<file> .
```
