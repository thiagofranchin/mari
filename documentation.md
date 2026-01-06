# General documentation

## Docker

Subir container

```
docker compose up
```

Para rodar em background (detach)

```
docker compose up -d
```

Quando o arquivo não esta na raiz e precisa especifica-lo

```
docker compose -f infra/compose.yaml up
```

Parar o container

```
docker compose -f infra/compose.yaml down
```

Listar container

```
docker ps -a
```

Recriar Container

```
docker compose up -d --force-recreate
```
