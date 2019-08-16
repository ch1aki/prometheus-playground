# prometheus-playground

## containers

- prometheus
- node-exporter
- alertmanager
- mailcatcher

## start

```
$ docker-compose up -d
```

## alertmanager test

1. stop `node`(node-exporter container)

    ```bash
    $ docker-compose stop node
    ```
    
1. check alert mail at `localhost:1080`
