redis
---

Configure and run unprivileged vanila Redis server as docker container into systemd.service.


### Links:
- <https://redis.io>
- <https://hub.docker.com/_/redis/>


### Variables:
- **`redis_docker_image`** *(type=string, default="redis:latest")* - Docker image for using into systemd.service.

- **`redis_uid`** & **`redis_gid`** *(type=number, default=6379)* - System user and group for run Redis server and store data.

- **`redis_config`** *(type=string, mandatory)* - Multiline content for Redis server config (`/etc/redis/server.conf`).
