## Prequisites
- A linux machine
- Docker and its prequisites installed
- Github account

##Setting up Saleor Platform
### Saleor -Dashboard

## Requirements
1. [Docker](https://docs.docker.com/install/)

2. For Saleor installation
   https://github.com/ravi-chhetri/isec6000-assignment1-task2


## How to run it?

2. Go to the cloned directory:
```
cd "your Directory name"
```

3. Build the application:
```shell
docker compose build
```

4. Apply Django migrations:
```shell
docker compose run --rm api python3 manage.py migrate
```

6. Run the application:
```shell
docker compose up
```

## Where is the application running?
- Saleor Core (API) - http://localhost:8000
- Saleor Dashboard - http://localhost:9003
- Jaeger UI (APM) - http://localhost:16686
- Mailpit (Test email interface) - http://localhost:8025


