unsafe-postgres
===============

```bash
# build
docker build -t unsafe_postgres .

# new container
docker run --name NAME -e POSTGRES_USER=$USER -p 5432:5432 unsafe_postgres -d
```
