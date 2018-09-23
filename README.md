# Bitu Cashflow

## Development

- `docker-compose up -d` (with `--build` if changes have been made to `Dockerfile` or `docker-compose.yml`)
- `docker exec -it cashflow_app_1 zsh`
- In the `cashflow_app_1` container run `npm start`
- Add `127.0.0.1 cashflow.local` to `/etc/hosts`
- The app is now available at `http://cashflow.local:2015`
