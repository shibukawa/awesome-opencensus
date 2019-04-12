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
  - [For Middlewares](#for-middlewares)
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
- [gomongowrapper](https://github.com/opencensus-integrations/gomongowrapper): MongoDB Go wrapper source code

### Java

- [opencensus-java](https://github.com/census-instrumentation/opencensus-java): 
- [opencensus-scala](https://github.com/census-ecosystem/opencensus-scala): Lightweight scala wrapper for the opencensus-java
- [opencensus-java-jdbc](https://github.com/census-ecosystem/opencensus-java-jdbc)
- [inspectIT Ocelot](http://docs.inspectit.rocks/releases/latest/)
- [ocspymemcached](https://github.com/opencensus-integrations/ocspymemcached): Spymemcached wrapper instrumented with OpenCensus

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
  - [Ruby on Rails](https://github.com/census-instrumentation/opencensus-ruby#getting-started-with-ruby-on-rails): Automatically tracing incoming requests in the application, database queries, view rendering
  - [Rack based frameworks](https://github.com/census-instrumentation/opencensus-ruby#getting-started-with-other-rack-based-frameworks): Automatically traces incoming requests

### Erlang/Elixir

- [opencensus-erlang](https://github.com/census-instrumentation/opencensus-erlang)

### Python

- [opencensus-python](https://github.com/census-instrumentation/opencensus-python)
  - [opencensus-ext-dbapi](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-dbapi): OpenCensus Database API Integration
  - [opencensus-ext-django](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-django): OpenCensus Django Integration
  - [opencensus-ext-flask](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-flask): OpenCensus Flask Integration
  - [opencensus-ext-django](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-django): OpenCensus Django Integration
  - [opencensus-ext-google-cloud-clientlibs](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-google-cloud-clientlibs): OpenCensus Google Cloud Client Libraries Integration
  - [opencensus-ext-grpc](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-grpc): OpenCensus gRPC Integration
  
  - [opencensus-ext-httplib](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-httplib): OpenCensus httplib Integration
  - [opencensus-ext-postgresql](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-postgresql): OpenCensus PostgreSQL([psycopg2](https://pypi.org/project/psycopg2)) Integration
  - [opencensus-ext-pymongo](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-pymongo): OpenCensus pymongo Integration
  - [opencensus-ext-pymysql](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-pymysql): OpenCensus PyMySQL Integration
  - [opencensus-ext-pyramid](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-pyramid): OpenCensus Pyramid Integration
  - [opencensus-ext-requests](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-requests): OpenCensus [requests](https://pypi.python.org/pypi/requests) Integration
  - [opencensus-ext-sqlalchemy](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-sqlalchemy): OpenCensus[SQLAlchemy](https://pypi.org/project/SQLAlchemy) Integration
  - [opencensus-ext-threading](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-threading): OpenCensus threading Integration
- [ocredispy](https://github.com/opencensus-integrations/ocredispy): OpenCensus wrapper for redis-py
- [ocpymemcache](https://github.com/opencensus-integrations/ocpymemcache): PyMemcache Python wrapper with observability provided by OpenCensus

### PHP

- [opencensus-python](https://github.com/census-instrumentation/opencensus-python): [Official ocument](https://opencensus.io/api/php/)
  - [Laravel integration document](https://opencensus.io/api/php/integrating-laravel/)
  - [Silex integration document](https://opencensus.io/api/php/integrating-silex/)
  - [Symfony integration document](https://opencensus.io/api/php/integrating-symfony/)
  - [WordPress integration document](https://opencensus.io/api/php/integrating-wordpress/)
  - [Guzzle HTTP Client integration document](https://opencensus.io/api/php/integrating-guzzle/)

### For Middlewares

- MongoDB
  - [mongostatusd](https://github.com/opencensus-integrations/mongostatusd): MongoDB server status daemon

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

- [LoggerExporter](https://www.rubydoc.info/gems/opencensus/OpenCensus/Trace/Exporters/Logger): Exporter JSON encoded spans to a standard Ruby Logger interface
- [opencensus-ruby-exporter-zipkin](https://github.com/census-ecosystem/opencensus-ruby-exporter-zipkin)

### Erlang/Elixir

#### Tracing

#### Stats/Metrics

### Python

#### Tracing

- [opencensus-ext-ocagent](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-ocagent): OpenCensus OC-Agent Trace Exporter
- [opencensus-ext-jaeger](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-jaeger): OpenCensus Jaeger Exporter
- [opencensus-ext-zipkin](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-zipkin): OpenCensus Zipkin Exporter

#### Stats/Metrics

- [opencensus-ext-prometheus](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-prometheus): OpenCensus Prometheus Exporter

### PHP


#### Tracing

- [StackdriverExporter](https://github.com/census-ecosystem/opencensus-php-exporter-stackdriver)
- [JaegerExporter](https://github.com/census-ecosystem/opencensus-php-exporter-jaeger)
- [ZipkinExporter](https://github.com/census-ecosystem/opencensus-php-exporter-zipkin)
- [InstanaExporter](https://github.com/census-ecosystem/opencensus-php-exporter-instana)
- [EchoExporter](https://opencensus.io/api/php/api/master/OpenCensus/Trace/Exporter/EchoExporter.html): Output the collected spans to stdout	
- [FileExporter](https://opencensus.io/api/php/api/master/OpenCensus/Trace/Exporter/FileExporter.html): Output JSON encoded spans to a file	
- [LoggerExporter](https://opencensus.io/api/php/api/master/OpenCensus/Trace/Exporter/LoggerExporter.html):	Exporter JSON encoded spans to a PSR-3 logger	
- [NullExporter](https://opencensus.io/api/php/api/master/OpenCensus/Trace/Exporter/NullExporter.html): No-op	
- [OneLineEchoExporter](https://opencensus.io/api/php/api/master/OpenCensus/Trace/Exporter/OneLineEchoExporter.html): Output the collected spans to stdout with one-line	

## Examples

### Go

- [go-kit-example](https://github.com/opencensus-integrations/go-kit-example): Go kit OpenCensus bootstrapping example
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
