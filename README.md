# docker_wrk_benchmark

## haw to use

```
docker run -it bootjp/docker_wrk_benchmark bash
wrk -t200 -c200 -d10m --timeout 5 http://bootjp.me
```
