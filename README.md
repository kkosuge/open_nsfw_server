### Usage

```
docker build -t open_nsfw_server:cpu ./
docker run --name nsfw_server -p 8080:80 -t open_nsfw_server:cpu
curl http://localhost:8080/nsfw_score?image_url=https://cdn-ak.f.st-hatena.com/images/fotolife/s/slideglide/20161020/20161020130337.jpg
```

### Open nsfw model
https://github.com/yahoo/open_nsfw
