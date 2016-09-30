# docker on wrk benchmark

## how to use
```bash
$ docker pull bootjp/docker_wrk_benchmark
$ docker run bootjp/docker_wrk_benchmark wrk -t20 -c20 -d10s --timeout 5 http://bootjp.me
```

## official source code repository

https://github.com/wg/wrk
