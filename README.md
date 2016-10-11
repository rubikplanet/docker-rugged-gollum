# docker-rugged-gollum
A Dockerfile to install gollum, default relied on rugged adapter and support full markups

## Usage

```sh
docker run -d -v /data/wiki:/wiki --name my-gollum-wiki -p 4567:4567 blackglory/rugged-gollum
```

You can attach some [gollum options](https://github.com/gollum/gollum#running) after image name.
