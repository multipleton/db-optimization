# db-optimization

## Docker

Before running `docker-compose up`, create the following folder structure for the database files:

```
└──opt
  └──oracle
    └──oradata
└──docker-compose.yml
```

then grant full access to the `oradata` directory by running the command:

```bash
$ sudo chmod -R 777 opt/oracle/oradata
```

After these steps, the database will be ready for initialization.

## Connection

Use the next credentials to access the local database:

- URL: `localhost:1521`
- Service: `xe`
- Username: `SYSTEM`
- Password: `password`
