## Running via Docker

First, create an external network in order to make the services from different compose files communicate with each other:

```bash
$ docker network create bank-microservices-network
```

Copy the `.env.template` file and configure it with your desired settings:

```bash
$ cp .env.template .env
```

Finally, you can start the services:

```bash
$ docker compose up -d
```
