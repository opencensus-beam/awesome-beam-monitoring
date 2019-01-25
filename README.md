Awesome BEAM Monitoring
=======================

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

The curated list of tools for monitoring, instrumenting, and tracing
applications that run on BEAM. Inspired by many of such lists over the GitHub.

## Logging

- [`lager`](https://github.com/erlang-lager/lager) - popular logging framework
  with broad features set
- [`logger`](http://www.erlang.org/doc/man/logger.html) - OTP 21+ built-in
  pluggable logger module
- [`Logger`](https://hexdocs.pm/logger/Logger.html) - Elixir's built-in
  pluggable logger module that in recent Elixir versions also synchronises with
  Erlang's `logger` module

## Metrics

- [Exometer](https://github.com/Feuerlabs/exometer_core) - Erlang
  instrumentation package
- [Elixometer](https://github.com/pinterest/elixometer) - thin Elixir wrapper
  over Exometer
- [Folsom](https://github.com/boundary/folsom) - expose Erlang events as metrics
- [`metrics`](https://github.com/benoitc/erlang-metrics) - generic interface to
  to a different metrics systems in Erlang
- [Telemetry](https://github.com/beam-telemetry/telemetry) - dynamic dispatcher
  for Erlang metrics and instrumentations
- [Telemetry.Poller](https://github.com/beam-telemetry/telemetry_poller) -
  periodically gather measurements and publish them as Telemetry events
- [Statix](https://github.com/lexmag/statix) - fast and reliable Elixir client
  for StatsD-compatible servers with some DogStatsD extensions (namely tags)
- [Fluxter](https://github.com/lexmag/fluxter) - InfluxDB writer for Elixir
- [Prometheus](https://github.com/deadtrickster/prometheus.erl) - Prometheus
  integration for Erlang

## Tracing

- [OpenCenus](https://github.com/census-instrumentation/opencensus-erlang) -
  implementation of Google's [OpenCensus.io](https://opencensus.io) tracing and
  monitoring with broad range of integrations:
  * [DataDog APM & DogStatsD](https://github.com/opencensus-beam/opencensus_datadog)
  * [Elixir](https://github.com/opencensus-beam/opencensus_elixir)
  * [Elli](https://github.com/opencensus-beam/opencensus_elli)
  * [Google Reporter](https://github.com/opencensus-beam/oc_google_reporter)
  * [InfluxDB](https://github.com/opencensus-beam/opencensus_influxdb)
  * [Plug](https://github.com/opencensus-beam/opencensus_plug)
  * [Prometheus](https://github.com/opencensus-beam/prometheus)
  * [Telemetry](https://github.com/opencensus-beam/opencensus_telemetry)
- [Spandex](https://github.com/spandex-project/spandex) - tracing library for
  Elixir which supports DataDog APM. Integrations:
  * [Ecto](https://github.com/spandex-project/spandex_ecto)
  * [Phoenix](https://github.com/spandex-project/spandex_phoenix)
- [tracelog](https://github.com/opencensus-beam/tracelog) - logging handler that
  can transform structured logs into distributed tracing spans (for now supports
  only OpenCensus backend library)

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](LICENSE).
