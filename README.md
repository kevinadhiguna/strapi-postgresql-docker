# 🌈 Strapi PostgreSQL - docker-compose

Strapi app with PostgreSQL powered by docker-compose.

<img src="https://s9.gifyu.com/images/cyyoung.png" alt="cyyoung.png" border="0" />

<br />

## Prerequisites :

You should have [docker](https://docs.docker.com/engine/install/) and [docker-compose](https://docs.docker.com/compose/install/) installed on your computer.

<br />

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

## Using Strapi with another Database Management System ?

Please feel free to have a look at :
- [Strapi MySQL - docker-compose](https://github.com/kevinadhiguna/strapi-mysql-docker)
- [Strapi MongoDB - docker-compose](https://github.com/kevinadhiguna/strapi-mongo-docker)
- [Strapi MariaDB - docker-compose](https://github.com/kevinadhiguna/strapi-mariadb-docker)

Thank you, have a nice day!

<br/>

![Hello !](https://api.visitorbadge.io/api/VisitorHit?user=kevinadhiguna&repo=strapi-postgresql-docker&label=thanks%20for%20dropping%20in%20!&labelColor=%23000000&countColor=%23FFFFFF)
