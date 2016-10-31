## Usage

#### Docker Hub

```
docker run -p 8080:80 -d -t kkosuge/open_nsfw_server:latest
curl http://localhost:8080/nsfw_score?image_url=https://cdn-ak.f.st-hatena.com/images/fotolife/s/slideglide/20161020/20161020130337.jpg
```

#### Github Checkout

```
git clone git@github.com:kkosuge/open_nsfw_server.git
cd open_nsfw_server
docker build -t open_nsfw_server:cpu ./
docker run --name nsfw_server -p 8080:80 -t open_nsfw_server:cpu
curl http://localhost:8080/nsfw_score?image_url=https://cdn-ak.f.st-hatena.com/images/fotolife/s/slideglide/20161020/20161020130337.jpg
```

## Open nsfw model
https://github.com/yahoo/open_nsfw
