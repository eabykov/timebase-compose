1. Requires [Docker](https://docs.docker.com/engine/install/) with [Compose](https://docs.docker.com/compose/cli-command/) plugin [v2.3.4](https://github.com/docker/compose/releases/tag/v2.3.4)
2. Up the project using command `docker compose up -d --wait`

## Links and images

| App | Port |
|-|-|
| TimeBase | 8011
| TimeBase Admin | 8099

![TimeBase Admin WEB UI](./images/timebase-admin.jpg)

## Usefull commands

| Command | Discription
|-|-
| `docker stats --no-stream` | Containers resource usage
| `docker compose logs` | Shows logs of containers (use flag `-f` to follow logs)
| `docker compose down` | Stop and remove containers (flag `-v` remove named volumes declared in the volumes section of the Compose file and anonymous volumes attached to containers)
| `docker system prune -a -f` | Remove all unused containers, networks, images (flag `--volumes` prune volumes)
