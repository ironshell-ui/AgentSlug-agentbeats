# Amber instructions

## Compile

```bash
./amber compile amber-scenario.json5 --docker-compose agentslug.yml
```

## Run

```bash
export $(grep -v '^#' .env | xargs) && docker compose -f agentslug.yml up
```
