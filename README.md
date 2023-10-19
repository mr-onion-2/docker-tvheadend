```bash
docker run --rm --privileged multiarch/qemu-user-static --reset -p yes
docker build --no-cache --pull -t securitybyte/tvheadend:goat .
docker push securitybyte/tvheadend:goat
```

