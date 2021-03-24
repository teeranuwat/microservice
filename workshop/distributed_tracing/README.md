# Tracing Using Jaeger
* Website : [Jaeger tracing server](https://www.jaegertracing.io/)

1. Start docker
```
    $docker container run \
        -d --rm --name tracer \
        -p 6831:6831/udp \
        -p 6832:6832/udp \
        -p 16686:16686 \
        jaegertracing/all-in-one \
        --log-level=debug

```
Start Jaeger Server on [localhost](http://localhost:16686/)
2. Start Services
```


``` 
