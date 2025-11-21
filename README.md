# Template API

## Setup:
```
uv sync
```

### Start with uv
```
uv run app
```

### Start with docker
```
docker compose up --build -d
```

## CLI:

### Create migration
```
uv run cli migration
```

### Upgrade database with alembic
```
uv run cli upgrade
```