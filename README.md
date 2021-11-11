# CLIC! image builder

Custom image for raspberry pi nano-computers, that is declined in two variants :

- Clic server : based on raspberry pi os lite, no X server and desktop, only server with yunohost packages installed
- Clic desktop : based on raspberry pi os, with X server and desktop with usefull desktop apps, and yunohost packages installed

:gear: Based [Pimod](https://github.com/Nature40/pimod.git), this repository is intended as a basic template for developers who wish to create ready-to-use bootstrap repositories meant for novice users. See [aniongithub/rhasspy-appliance](https://github.com/aniongithub/rhasspy-appliance) for an example of a repository meant for novice end-users to use directly.

## Run with docker

```bash
# build the docker container
docker build -t pimod .

# use docker-compose
docker-compose run pimod pimod.sh clic-server.Pifile
docker-compose run pimod pimod.sh clic-desktop.Pifile
```
