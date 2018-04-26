## This is Hongyi's Wepay Work Log Folder

## Kafka Connect BigQuery Connector Metrics

This is an integrated Java metrics library based on [Dropwizard/Metrics]. Developers can expose Waltz metrics to console, [JMX] or [StatsD], 
and eventually allow monitoring with Grafana/Prometheus.

### User Guide

The 5 types of metrics supported: Meter, Counter, Timer, Histogram, Gauge.<br />
The 3 types of reporter supported: ConsoleReporter, JmxReporter, StatsDReporter.

### Reference 

This libraray is built Dropwizard/Metrics open source project, including [metrics-core],
[metrics-jmx], and third-party [metrics-statsd]. 

  [JMX]: http://metrics.dropwizard.io/4.0.0/getting-started.html
  [StatsD]: https://github.com/etsy/statsd/
  [Dropwizard/Metrics]: https://github.com/dropwizard/metrics
  [metrics-core]: https://github.com/dropwizard/metrics/tree/4.1-development/metrics-core
  [metrics-jmx]: https://github.com/dropwizard/metrics/tree/4.1-development/metrics-jmx
  [metrics-statsd]: https://github.com/ReadyTalk/metrics-statsd
