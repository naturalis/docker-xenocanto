docker-xenocanto
====================

Docker compose file for adding minio to xenocanto infrastructure

Persistent volumes
 - "/data/minio:/data"  

webserver runs on port 8443

Contents
-------------


Instruction building image
-------------
No special instruction, repository can be used together with docker_compose puppet manifest. https://github.com/naturalis/puppet-docker_compose
```

```

Instruction running docker-compose.yml
-------------

#### preparation
- Copy env.template to .env and adjust variables. 
- Copy Traefik.toml.template to traefik.toml and add certificates


````
docker-compose up -d
````

Usage
-------------

````


````

