# oven-media-server

## Run with Docker

docker run --rm -p 1935:1935 -p 4000-4005:4000-4005/udp -p 3333:3333 -p 3478:3478 -p 8080:8080 -p 9000:9000 -p 8081:8081 -p 9090:9090 -p 9999:9999/udp -p 10006-10010:10006-10010/udp --network=bridge --name live-oven oven
