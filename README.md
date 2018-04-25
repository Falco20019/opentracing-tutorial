# OpenTracing Tutorials

A collection of tutorials for the OpenTracing API (https://opentracing.io).

## Installation

The tutorials are using CNCF Jaeger (https://github.com/jaegertracing/jaeger) as the tracing backend.
The full backend with a mock in-memory storage can be run as a single Docker container (one command):

```
docker run -d -p5775:5775/udp -p6831:6831/udp -p6832:6832/udp \
  -p5778:5778 -p16686:16686 -p14268:14268 -p9411:9411 jaegertracing/all-in-one:0.8.0
```

Once the container starts, the Jaeger UI will be accessible at http://localhost:16686.

## Tutorials by Language

  * [C# tutorial](./csharp/)
  * [Go tutorial](./go/)
  * [Java tutorial](./java)
  * [Python tutorial](./python)
  * [Node.js tutorial](./nodejs)
