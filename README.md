## Presenting exchange rates dataset
### Moving to PostgresSQL database and providing analysis queries

Currency Exchange Rates dataset: https://www.kaggle.com/datasets/ruchi798/currency-exchange-rates

Python, Postgres, Docker

### Dependencies:

```
pandas
matplotlib
numpy
psycopg2-binary
sqlalchemy
```

Building container on port 5433 
```
docker run --name postgres -e POSTGRES_PASSWORD=admin -e POSTGRES_USER=admin -e POSTGRES_HOST_AUTH_METHOD=trust -p 5433:5432 -d postgres
```