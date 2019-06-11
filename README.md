# Awesome OpenCensus



## Contents

Erlang/Elixir users -> See also [awesome-beam](https://github.com/opencensus-beam/awesome-beam-monitoring)

- [Instrumentation](#instrumentation)
  - [Go](#go)
  - [Java](#java)
  - [C#](#c)
  - [C++](#c-1)
  - [JavaScript](#javascript)
  - [Ruby](#ruby)
  - [Erlang/Elixir](#erlangelixir)
  - [Python](#python)
  - [PHP](#php)
  - [Clojure](#clojure)
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
  - [PHP](#php-1)
- [Useful Libraries](#useful-libraries)
- [Useful Tools](#useful-tools)
- [Examples](#examples)
  - [Go](#go-2)
  - [Java](#java-2)
  - [C#](#c-4)
  - [C++](#c-5)
  - [JavaScript](#javascript-6)
  - [Ruby](#ruby-7)
  - [Erlang/Elixir](#erlangelixir-1)
  - [Python](#python-2)
  - [PHP](#php-2)
  - [Scala](#scala)
  - [Kotlin](#kotlin)
- [Supported Backends](#supported-backends)
- [Resources](#resources)
  - [Websites](#websites)
  - [Training](#training)
  - [Community](#community)
  - [Influential Books](#influential-books)
- [Contributing](#contributing)

## Integrations

### Go

- [opencensus-go](https://github.com/census-instrumentation/opencensus-go)
  - [ocgrpc](https://godoc.org/go.opencensus.io/plugin/ocgrpc): Package ocgrpc contains OpenCensus stats and trace integrations for gRPC.
  - [ochttp](https://godoc.org/go.opencensus.io/plugin/ochttp): Package ochttp provides OpenCensus instrumentation for net/http package.
- [ocsql](https://github.com/opencensus-integrations/ocsql): OpenCensus SQL database driver wrapper for Go
- [gomongowrapper](https://github.com/opencensus-integrations/gomongowrapper): MongoDB Go wrapper source code
- [go-http-metrics](https://github.com/slok/go-http-metrics) by slok: It supports Go http.Handler, Negroni, httprouter, go-restful

### Java

- [opencensus-java](https://github.com/census-instrumentation/opencensus-java): 
- [opencensus-scala](https://github.com/census-ecosystem/opencensus-scala): Lightweight scala wrapper for the opencensus-java
- [opencensus-java-jdbc](https://github.com/census-ecosystem/opencensus-java-jdbc)
- [inspectIT Ocelot](http://docs.inspectit.rocks/releases/latest/)
- [ocspymemcached](https://github.com/opencensus-integrations/ocspymemcached): Spymemcached wrapper instrumented with OpenCensus
- [ocjedis](https://github.com/orijtech/ocjedis): Jedis wrapper instrumented with OpenCensus

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
  - [Opencensus.Plug](https://github.com/opencensus-beam/opencensus_plug): Plug integration for OpenCensus. It provides tracer and metrics integration.
  - [OpencensusPhoenix](https://github.com/opencensus-beam/opencensus_phoenix): Phoenix instrumenter callback module to automatically create OpenCensus spans for Phoenix Controller and View information.
  - [opencensus_cowboy](https://github.com/opencensus-beam/opencensus-cowboy): Opencensus Cowboy integration
  - [OpenCensus Tesla Middleware](https://github.com/opencensus-beam/opencensus_tesla): OpencensusTesla is a Tesla middleware for generating spans for outgoing requests
  - [opencensus_elli](https://github.com/opencensus-beam/opencensus_elli): Elli middleware for OpenCensus instrumentation.
  - [Opencensus.Telemetry](https://github.com/opencensus-beam/opencensus_telemetry): Opencensus integration with Telemetry library
  - [opencensus_vmstats](https://github.com/opencensus-beam/opencensus_vmstats): An OTP library
  - [tracelog](https://github.com/opencensus-beam/tracelog): A logging handler that can transforms structured logs into opencensus distributed tracing spans
- [opencensus_elixir](https://github.com/opencensus-beam/opencensus_elixir)

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

### Clojure

- [opencensus-clojure](https://github.com/uswitch/opencensus-clojure)

### For Middlewares

- MongoDB
  - [mongostatusd](https://github.com/opencensus-integrations/mongostatusd): MongoDB server status daemon
- StatsD
  - [stats-opencensus-backend](https://github.com/DazWilkin/statsd-opencensus-backend)

## Exporters

### Go

- [OpenCensus Agent](https://opencensus.io/exporters/supported-exporters/go/ocagent/)
- [Stackdriver](https://opencensus.io/exporters/supported-exporters/go/stackdriver/)
- [Datadog](https://opencensus.io/exporters/supported-exporters/go/datadog/)
- [krakend-opencensus](https://github.com/devopsfaith/krakend-opencensus) by @devopsfaith

#### Tracing

- [Honeycomb.io](https://opencensus.io/exporters/supported-exporters/go/honeycomb/)
- [Jaeger](https://opencensus.io/exporters/supported-exporters/go/jaeger/)
- [Zipkin](https://opencensus.io/exporters/supported-exporters/go/zipkin/)
- [AWS X-Ray](https://opencensus.io/exporters/supported-exporters/go/xray/)
- [AWS CloudWatch](https://github.com/fllaca/opencensus-cloudwatch-exporter)

#### Stats/Metrics

- [Prometheus](https://opencensus.io/exporters/supported-exporters/go/prometheus/)
- [opencensus-go-exporter-signalfx](https://github.com/census-ecosystem/opencensus-go-exporter-signalfx)
- [opencensus-go-exporter-graphite](https://github.com/census-ecosystem/opencensus-go-exporter-graphite)
- [opencensus-go-kafka-exporter](https://github.com/census-ecosystem/opencensus-go-kafka-exporter)
- InfluxDB
  - [github.com/egymgmbh/opencensus-go-exporter-influxdb](https://github.com/egymgmbh/opencensus-go-exporter-influxdb)
  - [github.com/kpacha/opencensus-influxdb](https://github.com/kpacha/opencensus-influxdb)

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
- [OpenCensus::Jaeger](https://github.com/Thinkei/opencensus-ruby-exporter-jaeger)

### Erlang/Elixir

- [OpenCensus Agent Reporter](https://github.com/opencensus-beam/opencensus_service): This reporter exports spans to the OpenCensus Agent in the standard protobuf format over grpc.
- [oc_datadog](https://github.com/opencensus-beam/opencensus_datadog): Opencensus integration to [DataDog][https://datadoghq.com] traces and metrics (via dogstatsd)

#### Tracing

- [OpenCensus Zipkin Reporter](https://github.com/opencensus-beam/opencensus_zipkin)
- [oc_google_reporter](https://github.com/opencensus-beam/oc_google_reporter): Reporter for opencensus that implements support for version 1 and 2 of [Google Cloud Trace](https://cloud.google.com/trace/docs/reference/)

#### Stats/Metrics

- [opencensus_influxdb](https://github.com/opencensus-beam/opencensus_influxdb)
- [Opencensus Prometheus integration](https://github.com/opencensus-beam/prometheus)

### Python

#### Tracing

- [opencensus-ext-ocagent](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-ocagent): OpenCensus OC-Agent Trace Exporter
- [opencensus-ext-jaeger](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-jaeger): OpenCensus Jaeger Exporter
- [opencensus-ext-zipkin](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-zipkin): OpenCensus Zipkin Exporter
- [ochoneycomb](https://github.com/codeboten/ochoneycomb): OpenCensus Python exporter for Honeycomb

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

## Useful Libraries

- [rpcx](https://github.com/smallnest/rpcx): Faster multil-language (java, php, python, c/c++, node.js, c#, etc...) bidirectional RPC framework in Go, like alibaba Dubbo, but with more features, Scale easily. Try it. Test it. If you feel it's better, use it!
- [ocgoconfig](https://github.com/bweston92/ocgoconfig): OpenCensus Configuration for Golang
- [OpenCensus Utils](https://github.com/QubitProducts/qubit-opencensus): A collection of tools for use with OpenCensus Python

## Useful Tools

- [Microsoft/ApplicationInsights-LocalForwarder](https://github.com/Microsoft/ApplicationInsights-LocalForwarder): Local Forwarder is an agent that collects Application Insights or OpenCensus telemetry from a variety of SDKs and routes it to the Application Insights backend.
- [opencensus-go-resource](https://github.com/census-ecosystem/opencensus-go-resource): This repository contains Go packages for auto discovery of resource information in various environments.
- [opencensus-php-docker](https://github.com/basvanbeek/opencensus-php-docker): OpenCensus PHP Ecosystem using Docker Compose for quick prototyping & testing.

## Examples

### Go

- [go-kit-example](https://github.com/opencensus-integrations/go-kit-example): Go kit OpenCensus bootstrapping example
- [opencensus-gokit-example](https://github.com/basvanbeek/opencensus-gokit-example)
- [Tutorial for OpenCensus for gRPC Go developers](https://github.com/orijtech/opencensus-for-grpc-go-developers)
- [Go OpenCensus example for Gin and Gorm](https://github.com/sagikazarmark/go-gin-gorm-opencensus)
- [opencensus-demos](https://github.com/orijtech/opencensus-demos)

### Java

- [gRPC/OpenCensus Demo](https://github.com/rakyll/opencensus-grpc-demo)
- [OpenCensus - A stats collection and distributed tracing framework](https://github.com/maurocanuto/distributed-tracing-opencensus)
- [Distributed tracing example with Opencensus and Jaeger](https://github.com/maurocanuto/distributed-tracing-opencensus)
- [OpenCensus for Java by Example](https://github.com/saturnism/opencensus-java-by-example)

### C#

- [Hipster Shop: Cloud-Native Microservices Demo Application](https://github.com/GoogleCloudPlatform/microservices-demo)
- [Collect distributed traces from Go (to Application Insights)](https://docs.microsoft.com/ja-jp/azure/azure-monitor/app/opencensus-go?WT.mc_id=ignite-twitter-brketels)

### C++

- [opencensus-for-grpc-cpp-developers](https://github.com/orijtech/opencensus-for-grpc-cpp-developers)

### JavaScript

- [Lightning-Talk Style Demo of Istio and OpenCensus](https://github.com/thesandlord/Istio101)

### Ruby

### Erlang/Elixir

### Python

- [OpenCensus for Python gRPC developers](https://medium.com/@orijtech/opencensus-for-python-grpc-developers-9e460e054395)

### PHP

### Scala

- [grpc opencensus example scala](https://github.com/jyane/grpc-opencensus-example-scala)

### Kotlin

- [OpenCensus Demo](https://github.com/athenian-programming/opencensus-demo)

## Supported Backends

## Resources

### Websites

* [OpenCensus](https://opencensus.io/)
  * [Twitter](https://twitter.com/opencensusio)
  * [GitHub: census-instrumentation org](https://github.com/census-instrumentation)
  * [GitHub: census-ecosystem org](https://github.com/census-ecosystem)
  * [GitHub: OpenCensus Integrations org](https://github.com/opencensus-integrations)
  * [GitHub: Opencensus.io integrations for Erlang, Elixir, and other BEAM languages](https://github.com/opencensus-beam)
* [OpenTracing](https://opentracing.io/)
  * [blog: Merging OpenTracing and OpenCensus: Goals and Non-Goals](https://medium.com/opentracing/merging-opentracing-and-opencensus-f0fe9c7ca6f0)

### Blogs

* [OpenCensus Service Configuration](https://omnition.io/blog/opencensus-service-configuration/)
* [Future Architect Tech Blog: What is OpenCensus(OpenTelemetry) (Japanese)](https://future-architect.github.io/articles/20190604/)

### Presentation

* [Troubleshoot Your RoR Microservices with Distributed Tracing](https://speakerdeck.com/kawasy/railsconf-2019-troubleshoot-your-ror-microservices-with-distributed-tracing) (at RailsConf 2019)

### Training

- [GoogleCloudPlatform/stackdriver-sandbox](https://github.com/GoogleCloudPlatform/stackdriver-sandbox)

### Community

#### Japan

* [OpenCensus meetup vol.1](https://opencensus.connpass.com/event/123885/): Tokyo 2019/Apr/03

## Contributing

Contributions are very welcome!
