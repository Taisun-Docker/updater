## Taisun ![Taisun](http://taisun.io/img/TaisunSmall.png)

http://taisun.io

Forked version of https://github.com/v2tec/watchtower that supports oneshot updating for an ephemeral container that can be used to pull the latest of an image at it's tag and replace it with the same env variables.

Usage :

```
sudo docker run --rm \
-v /var/run/docker.sock:/var/run/docker.sock taisun/updater \
--oneshot <Your Container Names>
```
