### lantern in ubuntu:16.04

### Usage

```sh
docker stop lantern && docker rm lantern

docker run --name lantern -d -p 8087:8087 -p 8086:8080 --restart=always \
  bjddd192/lantern:latest
```

