# Docker Demo

## Docksal in Docker

http://hub.docker.com/r/deciphered/docker-docksal/

```
docker run --rm -it -v $(PWD):/var/www -v /var/run/docker.sock:/var/run/docker.sock --name docksal deciphered/docksal:latest /bin/bash
fin up
```

## Drush use

`.drush-use` file in root of project points to the desired binary.

It can be pointed at a shell script that passes through the a variable version of drush based on situation.

E.g., If Docksal is running, pass through to `fin drush $@`.