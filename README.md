# Docker Demo

```
docker run --rm -it -v $(PWD):/var/www -v /var/run/docker.sock:/var/run/docker.sock --name docksal deciphered/docksal:latest /bin/bash
fin up
```