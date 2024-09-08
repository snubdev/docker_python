# Rodar o DOCKER NO CMD

### Acesse o diretorio do projeto


```
cd. project_one
```

### Construir a imagem Docker

```
docker build -t project_one
```
Esse comando criará uma imagem com nome 'project_one'

### Executa o container

```
docker run -p 5000:5000 project_one
```

## Docker Compose

Docker Compose irá construir e rodar a aplicação automaticemente

```
docker-compose up
```
