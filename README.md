Microsoft SQL Server

You need a ```.env``` file to set the required parameters.  It should look like this:

```bash
COMPOSE_PROJECT_NAME=mssql2017 # this should be unique for every version of postgres since the data volume will be persisted and will be named based on this value.
SA_PASSWORD=YourUserPasswordHere
```

Run ```docker-compose up``` to start the container.
