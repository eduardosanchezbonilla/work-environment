# EJECUTAR CONTENEDOR MONGO

```bash
- docker-compose up --build
```

```bash
- docker pull mongo:4.0.4
- docker run -d -p 27017-27019:27017-27019 --name mongodb mongo:4.0.4
```

# CONECTAR POR CONSOLA A MONGO

```bash
- winpty docker exec -it mongodb bash
```
