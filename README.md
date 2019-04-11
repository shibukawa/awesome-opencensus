# Awesome OpenCensus

## Contents

- [Instrumentation](#instrumentation)
  - [Go](#go)
  - [Java](#java)
  - [C#](#c)
  - [C++](#c-1)
  - [JavaScript](#javascript)
  - [Ruby](#ruby)
  - [Erlang/Elixir](#erlangelixir)
  - [Python](#python)
- [Exporters](#exporters)
  - [Go](#go-1)
  - [Java](#java-1)
  - [C#](#c-2)
  - [C++](#c-3)
  - [JavaScript](#javascript-1)
  - [Ruby](#ruby-1)
  - [Erlang/Elixir](#erlangelixir-1)
  - [Python](#python-1)
- [Examples](#examples)
  - [Go](#go-2)
  - [Java](#java-2)
  - [C#](#c-4)
  - [C++](#c-5)
  - [JavaScript](#javascript-6)
  - [Ruby](#ruby-7)
  - [Erlang/Elixir](#erlangelixir-1)
  - [Python](#python-1)
- [Supported Backends](#supported-backends)
- [Resources](#resources)
  - [Websites](#websites)
  - [Community](#community)
  - [Influential Books](#influential-books)
- [Contributing](#contributing)

## Instrumentation

### Go

- [opencensus-go](https://github.com/census-instrumentation/opencensus-go)
- [ocsql](https://github.com/opencensus-integrations/ocsql): OpenCensus SQL database driver wrapper for Go

### Java

- [opencensus-java](https://github.com/census-instrumentation/opencensus-java): 
- [opencensus-scala](https://github.com/census-ecosystem/opencensus-scala): Lightweight scala wrapper for the opencensus-java
- [opencensus-java-jdbc](https://github.com/census-ecosystem/opencensus-java-jdbc)
- [inspectIT Ocelot](http://docs.inspectit.rocks/releases/latest/)

### C#

- [opencensus-csharp](https://github.com/census-instrumentation/opencensus-csharp)
  - [ASP.NET Core incoming requests collector](https://github.com/census-instrumentation/opencensus-csharp/#using-aspnet-core-incoming-requests-collector)
  - [Outgoing http calls made by .NET Core HttpClient](https://github.com/census-instrumentation/opencensus-csharp/#using-dependencies-collector)
  - [StackExchange.Redis collector](https://github.com/census-instrumentation/opencensus-csharp/#using-stackexchangeredis-collector)

### C++

- [opencensus-cpp](https://github.com/census-instrumentation/opencensus-cpp)

### JavaScript

- [opencensus-node](https://github.com/census-instrumentation/opencensus-node) 
  - [HTTP](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-instrumentation-http/README.md)
  - [HTTPS](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-instrumentation-https/README.md)
  - [HTTP2](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-instrumentation-http2/README.md)
  - [GRPC](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-instrumentation-grpc/README.md)
  - [IORedis](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-instrumentation-ioredis/README.md)
  - [Redis](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-instrumentation-redis/README.md)
- [opencensus-web](https://github.com/census-instrumentation/opencensus-web): Experimental pre-alpha stage

### Ruby

- [opencensus-ruby](https://github.com/census-instrumentation/opencensus-ruby)

### Erlang/Elixir

- [opencensus-erlang](https://github.com/census-instrumentation/opencensus-erlang)

### Python

- [opencensus-python](https://github.com/census-instrumentation/opencensus-python)

## Exporters

### Go

- [OpenCensus Agent](https://opencensus.io/exporters/supported-exporters/go/ocagent/)
- [Stackdriver](https://opencensus.io/exporters/supported-exporters/go/stackdriver/)
- [Datadog](https://opencensus.io/exporters/supported-exporters/go/datadog/)
- [KrakenD](https://github.com/devopsfaith/krakend-opencensus) by @devopsfaith

#### Tracing

- [Honeycomb.io](https://opencensus.io/exporters/supported-exporters/go/honeycomb/)
- [Jaeger](https://opencensus.io/exporters/supported-exporters/go/jaeger/)
- [Zipkin](https://opencensus.io/exporters/supported-exporters/go/zipkin/)
- [AWS X-Ray](https://opencensus.io/exporters/supported-exporters/go/xray/)

#### Stats/Metrics

- [Prometheus](https://opencensus.io/exporters/supported-exporters/go/prometheus/)
- [opencensus-go-exporter-signalfx](https://github.com/census-ecosystem/opencensus-go-exporter-signalfx)
- [opencensus-go-exporter-graphite](https://github.com/census-ecosystem/opencensus-go-exporter-graphite)
- [opencensus-go-kafka-exporter](https://github.com/census-ecosystem/opencensus-go-kafka-exporter)
- [InfluxDB](https://github.com/egymgmbh/opencensus-go-exporter-influxdb)

### Java

- [OpenCensus Agent](https://opencensus.io/exporters/supported-exporters/java/ocagent/)
- Stackdriver: [Tracing](https://opencensus.io/exporters/supported-exporters/java/stackdriver-trace/) [Stats](https://opencensus.io/exporters/supported-exporters/java/stackdriver-stats/)
- [AWS X-Ray](https://github.com/shirou/opencensus-exporter-trace-xray) by [@shirou](https://github.com/shirou)

#### Tracing

- [Jaeger](https://opencensus.io/exporters/supported-exporters/java/jaeger/)
- [Zipkin](https://opencensus.io/exporters/supported-exporters/java/zipkin/)
- [Instana](https://opencensus.io/exporters/supported-exporters/java/instana/)
- [Datadog](https://github.com/census-instrumentation/opencensus-java/tree/master/exporters/trace/datadog)
- [Logging](https://github.com/census-instrumentation/opencensus-java/tree/master/exporters/trace/logging)
- [LightStep](https://github.com/lightstep/lightstep-census-java)

#### Stats/Metrics

- [SignalFx](https://opencensus.io/exporters/supported-exporters/java/signalfx/)
- [Prometheus](https://opencensus.io/exporters/supported-exporters/java/prometheus/)

### C#

- [Stackdriver](https://github.com/census-instrumentation/opencensus-csharp/#using-stackdriver-exporter)
- [Azure Application Insights](https://github.com/census-instrumentation/opencensus-csharp/#using-application-insights-exporter)

#### Tracing

- [Zipkin](https://github.com/census-instrumentation/opencensus-csharp/#using-zipkin-exporter)

#### Stats/Metrics

- [Prometheus](https://github.com/census-instrumentation/opencensus-csharp/#using-prometheus-exporter)

### C++

- [Stackdriver](https://github.com/census-instrumentation/opencensus-cpp/blob/master/opencensus/exporters/stats/stackdriver/README.md)
- Stdout: [Tracing](https://github.com/census-instrumentation/opencensus-cpp/tree/master/opencensus/exporters/trace/stdout), [Stats](https://github.com/census-instrumentation/opencensus-cpp/tree/master/opencensus/exporters/stats/stdout)

#### Tracing

- [Zipkin](https://github.com/census-instrumentation/opencensus-cpp/tree/master/opencensus/exporters/trace/zipkin
)

#### Stats/Metrics

- [Prometheus](https://github.com/census-instrumentation/opencensus-cpp/tree/master/opencensus/exporters/stats/prometheus)

### JavaScript

- Node.js
  - [Stackdriver](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-exporter-stackdriver/README.md)

#### Tracing

- Node.js
  - [Jaeger](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-exporter-jaeger/README.md)
  - [Zipkin](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-exporter-zipkin/README.md)
  - [Instana](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-exporter-instana/README.md)

#### Stats/Metrics

- Node.js
  - [Prometheus](https://github.com/census-instrumentation/opencensus-node/blob/master/packages/opencensus-exporter-prometheus/README.md)

### Ruby

- [opencensus-ruby-exporter-ocagent](https://github.com/census-ecosystem/opencensus-ruby-exporter-ocagent)
- [opencensus-ruby-exporter-stackdriver](https://github.com/census-ecosystem/opencensus-ruby-exporter-stackdriver)

#### Tracing

- [opencensus-ruby-exporter-zipkin](https://github.com/census-ecosystem/opencensus-ruby-exporter-zipkin)

### Erlang/Elixir

#### Tracing

#### Stats/Metrics

### Python

#### Tracing

#### Stats/Metrics

### PHP

- [opencensus-php-exporter-stackdriver](https://github.com/census-ecosystem/opencensus-php-exporter-stackdriver)

#### Tracing

- [opencensus-php-exporter-jaeger](https://github.com/census-ecosystem/opencensus-php-exporter-jaeger)
- [opencensus-php-exporter-zipkin](https://github.com/census-ecosystem/opencensus-php-exporter-zipkin)
- [opencensus-php-exporter-instana](https://github.com/census-ecosystem/opencensus-php-exporter-instana)

## Examples

### Go

- [opencensus-gokit-example](https://github.com/basvanbeek/opencensus-gokit-example)
- [Tutorial for OpenCensus for gRPC Go developers](https://github.com/orijtech/opencensus-for-grpc-go-developers)

### Java

- [gRPC/OpenCensus Demo](https://github.com/rakyll/opencensus-grpc-demo)
- [OpenCensus - A stats collection and distributed tracing framework](https://github.com/maurocanuto/distributed-tracing-opencensus)

### C#

- [Hipster Shop: Cloud-Native Microservices Demo Application](https://github.com/GoogleCloudPlatform/microservices-demo)

### C++

### JavaScript

- [Lightning-Talk Style Demo of Istio and OpenCensus](https://github.com/thesandlord/Istio101)

### Ruby

### Erlang/Elixir

### Python

## Supported Backends

## Resources

### Websites

* [OpenCensus](https://opencensus.io/)
  * [Twitter](https://twitter.com/opencensusio)
  * [GitHub: census-instrumentation org](https://github.com/census-instrumentation)
  * [GitHub: census-ecosystem org](https://github.com/census-ecosystem)
  * [GitHub: OpenCensus Integrations org](https://github.com/opencensus-integrations)
* [OpenTracing](https://opentracing.io/)
  * [blog: Merging OpenTracing and OpenCensus: Goals and Non-Goals](https://medium.com/opentracing/merging-opentracing-and-opencensus-f0fe9c7ca6f0)

### Community

#### Japan

* [OpenCensus meetup vol.1](https://opencensus.connpass.com/event/123885/): Tokyo 2019/Apr/03

## Contributing

Contributions are very welcome!
