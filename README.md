# docker-traefik

Docker + Traefik Example

## Prerequisites

- `docker-compose` is installed
- port 80 is not occupied

## Installation

1. Configure Hosts file:

```
# /etc/hosts

127.0.0.1     blog.myserver.test
127.0.0.1     wiki.myserver.test
```

2. Run docker-compose

```bash
$ docker-compose up -d
```

3. View in browser

- Ghost: `localhost:5001` or `blog.myserver.test`
- Dokuwiki: `localhost:5002` or `wiki.myserver.test`
- Traefik Web UI: `localhost:5003`
