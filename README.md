<p align="center"><img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/320/apple/198/fire-extinguisher_1f9ef.png" width="120px"></p>
<h1 align="center">haproxy_exporter (container image)</h1>
<p align="center">Built-from-source container image of <a href="https://prometheus.io/">Prometheus</a>' <a href="https://github.com/prometheus/haproxy_exporter">HAProxy exporter</a></p>


## Tags

### Docker Hub

Available on Docker Hub as [`docker.io/ricardbejarano/haproxy_exporter`](https://hub.docker.com/r/ricardbejarano/haproxy_exporter):

- [`0.13.0`, `latest` *(Dockerfile)*](Dockerfile)

### RedHat Quay

Available on RedHat Quay as [`quay.io/ricardbejarano/haproxy_exporter`](https://quay.io/repository/ricardbejarano/haproxy_exporter):

- [`0.13.0`, `latest` *(Dockerfile)*](Dockerfile)


## Features

* Compiled from source during build time
* Built `FROM scratch`, with zero bloat
* Statically linked to the [`musl`](https://musl.libc.org/) implementation of the C standard library
* Reduced attack surface (no shell, no UNIX tools, no package manager...)
* Runs as unprivileged (non-`root`) user


## Building

```bash
docker build --tag ricardbejarano/haproxy_exporter --file Dockerfile .
```


## License

MIT licensed, see [LICENSE](LICENSE) for more details.
