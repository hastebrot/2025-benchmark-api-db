# 2025-benchmark-api-db

docker images:
- https://hub.docker.com/_/python/tags?name=3.13-alpine
  - `docker pull --platform=linux/amd64 python:3.13-alpine` (16.02 MB)
- https://hub.docker.com/r/oven/bun/tags?name=1.2-alpine
  - `docker pull --platform=linux/amd64 oven/bun:1.2-alpine` (41.66 MB)
- https://hub.docker.com/_/redis/tags?name=8-alpine
  - `docker pull --platform=linux/amd64 redis:8-alpine` (23.2 MB)
- https://hub.docker.com/_/mongo/tags?name=8
  - `docker pull --platform=linux/amd64 mongo:8` (278.6 MB)
- https://hub.docker.com/_/postgres/tags?name=17-alpine
  - `docker pull --platform=linux/amd64 postgres:17-alpine` (105.65 MB)
 
wasm repositories:
- sqlite, https://github.com/DallasHoff/sqlocal
  - `bun add -D sqlocal`
- postgres, https://github.com/electric-sql/pglite
  - `bun add -D @electric-sql/pglite`
- surrealdb, https://github.com/surrealdb/surrealdb.wasm
  - `bun add -D @surrealdb/wasm`

documentation:
- https://github.com/mongodb/mongo-python-driver
- https://github.com/mongodb/node-mongodb-native
- https://github.com/fastapi/fastapi
- https://bun.sh/docs/api/http
- https://bun.sh/docs/api/redis
- https://bun.sh/docs/api/sql
- https://github.com/porsager/postgres
- https://www.mongodb.com/developer/languages/javascript/bun-with-mongodb/
- https://bun.sh/guides/ecosystem/mongoose
- https://bun.sh/guides/ecosystem/hono
