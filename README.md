# BBB docker-compose

O docker-compose é instalado junto com o Docker Desktop, siga a [docs](https://docs.docker.com/desktop/)

Para subir os serviços use o comando
```shell
docker-compose up
```

Para rodar em Background use a tag -d
```shell
docker-compose up -d
```

Frontend roda na http://127.0.0.1:8080

Backend roda na http://127.0.0.1:8000, verifique http://127.0.0.1:8000/docs

Parar os serviços com o comando 
```shell
docker-compose down
``` 