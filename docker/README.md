# docker

## basic docker commands

| command                   | result                         |
| ------------------------- | ------------------------------ |
| `docker images`           | list images                    |
| `docker ps -a`            | show all containers            |
| `docker image prune`      | remove unused images           |
| `docker build`            | build image from Dockerfile    |
| `docker run`              | run command in new container   |
| `docker stop <container>` | stop container (by name or ID) |

Apparently, ID/names don't need to be provided in full, e.g. first two bytes/chars may be enough if unique.
