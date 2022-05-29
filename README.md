# Database container
```
docker run --name some-postgres -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres
```

# For powershell (not cmd) :
```
$env:DB_USERNAME = "postgres"
$env:DB_PASSWORD = "postgres"
$env:DB_TABLE = "postgres"
$env:DB_PORT = "5432"
$env:DB_HOST ="localhost"
```

# For bash :
```
export DB_USERNAME=postgres
export DB_PASSWORD=postgres
export DB_TABLE=postgres
export DB_PORT=5432
export DB_HOST=localhost
```
