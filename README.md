# Clickhouse

[Репозиторий](https://github.com/zhmu-100/Clickhouse/tree/feat/Clickhouse)

Ветка - feat/Clickhouse

**Расположение .env файла - в корне (там же, где и build.gradle.kts)**

.env файл:
```
CLICKHOUSE_URL=jdbc:clickhouse://localhost:8123/test_db
CLICKHOUSE_USER=default
CLICKHOUSE_PASSWORD=

API_HOST=0.0.0.0
API_PORT=8080
```

# DB

[Репозиторий](https://github.com/zhmu-100/DB/tree/dev)

Ветка - dev

**Расположение .env файла - в корне (там же, где и build.gradle.kts)**

.env файл:
```
DB_HOST=localhost
DB_PORT=5432
DB_NAME=test_orm
DB_USER=postgres
DB_PASSWORD=password
PORT=8081
```

# FeedService

[Репозиторий](https://github.com/zhmu-100/FeedService/tree/dev)

Ветка - dev

**Расположение .env файла - в папке app (там же, где и build.gradle.kts)**

.env файл:
```
PORT=8082

DB_MODE=LOCAL # LOCAL or gateway
DB_HOST=localhost
DB_PORT=8081
```

# FileService

[Репозиторий](https://github.com/zhmu-100/FileService/tree/dev)

Ветка - dev

**Расположение .env файла - в папке app (там же, где и build.gradle.kts)**

.env файл:
```
MINIO_ENDPOINT=http://192.168.31.209:9000
MINIO_ACCESS_KEY=yEQiIkgvZIltX4P0ILID
MINIO_SECRET_KEY=V28Y73MJne6Mc6Ag3CoS7yMy5kCox6ejhKZKQZ28
MINIO_BUCKET_NAME=test-bucket
API_HOST=0.0.0.0
API_PORT=8080
```

# NotesService

[Репозиторий](https://github.com/zhmu-100/NotesService/tree/dev)

Ветка - dev

**Расположение .env файла - в папке app (там же, где и build.gradle.kts)**

.env файл:
```
SERVICE_PORT=8001

DB_MODE=LOCAL        # LOCAL or gateway
DB_HOST=localhost
DB_PORT=8082
```

# ProfileService

[Репозиторий](https://github.com/zhmu-100/ProfileService/tree/dev)

Ветка - dev

**Расположение .env файла - в папке app (там же, где и build.gradle.kts)**

.env файл:
```
PORT=8081

DB_MODE=LOCAL     # LOCAL or gateway
DB_HOST=localhost
DB_PORT=8082
```

# DietService

[Репозиторий](https://github.com/zhmu-100/DietService/tree/dev)

Ветка - dev

**Расположение .env файла - в папке app (там же, где и build.gradle.kts)**

.env файл:
```
PORT=8082

DB_MODE=LOCAL        # LOCAL or gateway
DB_HOST=localhost
DB_PORT=8081
```