# docker-postgres

## Build

```bash
$ git clone git@github.com:vedarthk/docker-postgres.git
$ docker build -t postgres .
```

## Run

```bash
$ docker run --name pg_container -e POSTGRES_PASSWORD=mysecretpassword -d vedarthk/postgres:9.5

```
