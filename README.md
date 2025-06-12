# 2025-benchmark-api-db

guides:
- [sdk concepts](guides/sdk-concepts.md)

example data:
- https://github.com/lgreski/pokemonData/blob/master/Pokemon.csv
  - "National Pokédex that brings the total number of Pokémon up to 1,025."
- https://github.com/Purukitto/pokemon-data.json/blob/master/pokedex.json
- https://www.kaggle.com/datasets/rounakbanik/pokemon

docker images
- https://hub.docker.com/_/python/tags?name=3.13-alpine
  - `docker pull --platform=linux/amd64 python:3.13-alpine` (3.13.4, 16.02 MB)
- https://hub.docker.com/r/oven/bun/tags?name=1.2-alpine
  - `docker pull --platform=linux/amd64 oven/bun:1.2-alpine` (1.2.16, 41.66 MB)
- https://hub.docker.com/_/redis/tags?name=8-alpine
  - `docker pull --platform=linux/amd64 redis:8-alpine` (8.0.2, 23.2 MB)
- https://hub.docker.com/_/mongo/tags?name=8
  - `docker pull --platform=linux/amd64 mongo:8` (8.0.10, 278.6 MB)
- https://hub.docker.com/_/postgres/tags?name=17-alpine
  - `docker pull --platform=linux/amd64 postgres:17-alpine` (17.5, 105.65 MB)
- https://hub.docker.com/r/surrealdb/surrealdb/tags?name=v2.3
  - `docker pull --platform=linux/amd64 surrealdb/surrealdb:v2.3` (2.3.3, 28.53 MB)
- https://hub.docker.com/r/datacatering/duckdb/tags?name=v1.3.0
  - `docker pull --platform=linux/amd64 datacatering/duckdb:v1.3.0` (1.3.0, 77.55 MB)
- https://hub.docker.com/_/golang/tags?name=1.24-alpine
  - `docker pull --platform=linux/amd64 golang:1.24-alpine` (1.24.4, 79.23 MB)
 
wasm repositories:
- sqlite, https://github.com/sqlite/sqlite-wasm
  - `bun add -D @sqlite.org/sqlite-wasm`
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

supabase docker images:

```
C:\>docker image ls | sort
REPOSITORY                              TAG                      IMAGE ID       CREATED        SIZE
public.ecr.aws/supabase/edge-runtime    v1.67.4                  358930e39ff3   2 months ago   1.01GB
public.ecr.aws/supabase/gotrue          v2.174.0                 15c64f5e56c2   2 weeks ago    71.7MB
public.ecr.aws/supabase/kong            2.8.1                    1b53405d8680   2 years ago    203MB
public.ecr.aws/supabase/logflare        1.12.0                   84d0cda731e1   3 months ago   721MB
public.ecr.aws/supabase/mailpit         v1.22.3                  f7f7c31de4de   3 months ago   43.5MB
public.ecr.aws/supabase/postgres-meta   v0.89.3                  8af5e9c9c336   2 weeks ago    548MB
public.ecr.aws/supabase/postgres        15.8.1.085               af083ef64d04   5 weeks ago    3GB
public.ecr.aws/supabase/postgrest       v12.2.12                 5f4ce744539b   7 months ago   22.8MB
public.ecr.aws/supabase/realtime        v2.36.7                  8c90870adf86   9 days ago     255MB
public.ecr.aws/supabase/storage-api     v1.23.0                  71d566d9d5b9   2 weeks ago    916MB
public.ecr.aws/supabase/studio          2025.06.02-sha-8f2993d   8ace6e32e26d   10 days ago    1.1GB
public.ecr.aws/supabase/vector          0.28.1-alpine            4bc04aca94a4   2 years ago    174MB
```
