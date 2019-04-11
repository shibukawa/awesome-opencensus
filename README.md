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
- [Supported Backends](#supported-backends)
- [Resources](#resources)
  - [Websites](#websites)
  - [Community](#community)
  - [Influential Books](#influential-books)
- [Contributing](#contributing)

## Instrumentation

### Go

- [opencensus-go](https://github.com/census-instrumentation/opencensus-go)

### Java

- [opencensus-java](https://github.com/census-instrumentation/opencensus-java): 
- [opencensus-scala](https://github.com/census-ecosystem/opencensus-scala): Lightweight scala wrapper for the opencensus-java
- [opencensus-java-jdbc](https://github.com/census-ecosystem/opencensus-java-jdbc)
- [inspectIT Ocelot](http://docs.inspectit.rocks/releases/latest/)

### C#

- [opencensus-csharp](https://github.com/census-instrumentation/opencensus-csharp)

### C++

- [opencensus-cpp](https://github.com/census-instrumentation/opencensus-cpp)

### JavaScript

- [opencensus-node](https://github.com/census-instrumentation/opencensus-node) 
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

#### Stats/Metrics

- [SignalFx](https://opencensus.io/exporters/supported-exporters/java/signalfx/)
- [Prometheus](https://opencensus.io/exporters/supported-exporters/java/prometheus/)

### C#

#### Tracing

#### Stats/Metrics

### C++

#### Tracing

#### Stats/Metrics

### JavaScript

#### Tracing

#### Stats/Metrics

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

## Supported Backends

## Resources

### Websites

* [OpenCensus](https://opencensus.io/)
  * [GitHub: census-instrumentation org](https://github.com/census-instrumentation)
  * [GitHub: census-ecosystem org](https://github.com/census-ecosystem)
* [OpenTracing](https://opentracing.io/)
  * [blog: Merging OpenTracing and OpenCensus: Goals and Non-Goals](https://medium.com/opentracing/merging-opentracing-and-opencensus-f0fe9c7ca6f0)

### Community

#### Japan

* [OpenCensus meetup vol.1](https://opencensus.connpass.com/event/123885/): Tokyo 2019/Apr/03

## Contributing

Contributions are very welcome!
