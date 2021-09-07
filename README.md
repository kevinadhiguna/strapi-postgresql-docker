# Strapi PostgreSQL - docker-compose

🌈 Strapi app with PostgreSQL powered by docker-compose

## Prerequisites :

You should have [docker](https://docs.docker.com/engine/install/) and [docker-compose](https://docs.docker.com/compose/install/) installed on your computer.

## How to Run :

1) Clone this repository :
```bash
git clone https://github.com/kevinadhiguna/strapi-postgresql-docker
```

2) Create `.env` file :
```bash
cp .env.example .env
```

Then please fill the `.env` file.

3) Run your app with `docker-compose` (in detached mode, you will not be seeing logs of your app) :
```bash
docker-compose -f strapi-postgresql.yml up -d
```

If you want to see the logs while running your app, run it with :
```bash
docker-compose -f strapi-postgresql.yml up
```

You can visit your app at `http://localhost:1337` in your browser.

<br/>

[![Visits Badge](https://badges.pufler.dev/visits/kevinadhiguna/strapi-postgresql-docker)](https://github.com/kevinadhiguna)
