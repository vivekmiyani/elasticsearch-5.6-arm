# Elasticsearch 5.6

This repo is to run elasticsearch 5.6 on ARM based machines.

# Build

You need to build the container using given Dockerfile:

```sh
docker build -f Dockerfile -t elastic .
```

Start the container:

```sh
docker run -p 9200:9200 -p 9300:9300 elastic
```
