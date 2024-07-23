# Symfony Project

- Symfony docker - https://github.com/dunglas/symfony-docker.git

- Docs : https://github.com/dunglas/symfony-docker?tab=readme-ov-file#getting-started

- Clean repo - Commit - https://github.com/fadilxcoder/sf7-multi-app/commit/87b48b05ceef9fb98fdde4e6e292b6162c741774

- Run `docker compose build --no-cache` to build fresh images

- Run `docker compose up --pull always -d --wait` to set up and start a fresh Symfony project **First time only**

- `docker compose up -d`

- Open `https://localhost` in your favorite web browser and [accept the auto-generated TLS certificate](https://stackoverflow.com/a/15076602/1352334)

- Run `docker compose down --remove-orphans` to stop the Docker containers.


## Docs

- https://localhost/
- https://localhost/_profiler/empty/search/results?limit=10
- Install profiler : `composer req symfony/web-profiler-bundle --dev`
