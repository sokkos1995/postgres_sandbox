# Репозиторий для изучения Postgres

## Описание

Используется 
```bash
wget https://storage.googleapis.com/thaibus/thai_small.tar.gz && tar -xf thai_small.tar.gz && psql < thai.sql
```

## Useful

```sql
\? -- show help on backslash commands
\h -- help on syntax of SQL commands, * for all commands

-- Informational
\d[S+]  -- list tables, views, and sequences
\dt[S+]  -- list tables
\l[+]  -- list databases
\dn[S+]  -- list schemas
```

## TODO

- выписать частоиспользуемые команды и что они значать из \? (\d, \u, \dt ... )