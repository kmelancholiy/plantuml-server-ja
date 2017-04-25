# docker-plantuml-server

* [plantuml-server](https://github.com/plantuml/plantuml-server) in Docker.
* [neam/docker-plantuml-server](https://github.com/neam/docker-plantuml-server) japanese fonts added.

## Usage

```sh
# either run in foreground (ctrl-c exits the server)
docker run -it -p 8080:8080 --rm kmelancholiy/plantuml-server-ja

# or in background (server keeps running until specifically killed)
docker logs -f $(docker run -d -p 8080:8080 kmelancholiy/plantuml-server-ja)
```

Visit http://ip-of-your-docker-host:8080 in your browser
