# docker-thor
Docker container with installed app thor for testing websockets connetions

### Which app is dockerized ?
 `https://github.com/observing/thor`

### How to use ?
docker run -it --rm fadeev2010/thor /usr/local/bin/thor --amount 10000 --messages 10 "wss://YOUR_URL"
