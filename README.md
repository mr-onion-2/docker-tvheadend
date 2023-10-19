```bash
docker run --rm --privileged multiarch/qemu-user-static --reset -p yes
docker build --no-cache --pull -t lscr.io/linuxserver/tvheadend:latest .
```

