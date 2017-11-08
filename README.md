# docker-thor
Docker container with installed app thor for testing websockets connetions

### Which app is dockerized ?
 `https://github.com/observing/thor`

### Pull container
`docker pull fadeev2010/docker-thor`

### How to use ?
`docker run -it --rm fadeev2010/docker-thor /usr/local/bin/thor --amount 10000 --messages 10 "wss://YOUR_URL"`
