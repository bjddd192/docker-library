## lantern

### Use

```sh
docker stop lantern && docker rm lantern

docker run --name lantern -d -p 8087:8087 -p 8086:8080 --restart=always \
  bjddd192/lantern:latest
```
	
#### 温馨提示，可以设置定时重启，防止800M流量后限速


