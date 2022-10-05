# Network Programming, TUM

First web server is `Factory-Module`, which produces some data and send it to the second web server, which is called `Delivery-Module`, that consumes that data from a Thread-Safe queue by marking every object as **delivered** and sends it back to the first server.

## Setup and running

First clone the repository 

```
https://github.com/creestee/pr
```

After that, make sure you have Docker and Docker Compose installed and also check that docker service is running inside your OS

https://docs.docker.com/engine/install/

Finally, run command, that starts up both containers

```
docker compose up --build
```