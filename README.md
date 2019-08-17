# prometheus-playground

## containers

- prometheus (`http://localhost:9090`)
- node-exporter (`http://localhost:9100`)
- alertmanager (`http://localhost:9093`)
- mailcatcher (`http://localhost:1080`)

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
