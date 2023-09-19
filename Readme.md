# Loja de produtos - Doceria

## Rodando localmente

Clone o projeto

```bash
  git clone https://github.com/ViniciusCosta126/loja_produtos
```

Entre no diretório do projeto

```bash
  cd my-project
```

Altere as variaveis de ambiente

```bash
  SECRET_KEY="CHANGE-ME"

    # 0 False, 1 True
    DEBUG="1"

    # Comma Separated values
    ALLOWED_HOSTS="127.0.0.1, localhost"

    DB_ENGINE="django.db.backends.postgresql"
    POSTGRES_DB="CHANGE-ME"
    POSTGRES_USER="CHANGE-ME"
    POSTGRES_PASSWORD="CHANGE-ME"
    POSTGRES_HOST="localhost"
    POSTGRES_PORT="5432"
```

Inicie o servidor

```bash
  docker-compose up --build
```
