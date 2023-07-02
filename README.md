# Observability demo

Demo of observing a Spring Boot application
([Spring Pet Clinic](https://github.com/spring-projects/spring-petclinic)).

What's observed:
* Metrics
* Logs
* Distributed tracing

Technologies used:
* [k3s](https://k3s.io/)
* [Helm](https://helm.sh/)
* [Reloader](https://github.com/stakater/Reloader)
* [Cert Manager](https://cert-manager.io/)
* [Postgres Operator](https://github.com/zalando/postgres-operator)
* [Paketo Buildpacks](https://paketo.io/)
* [Micrometer](https://micrometer.io/)
* [OpenTelemetry Java Agent](https://opentelemetry.io/docs/instrumentation/java/automatic/)
* [Grafana](https://grafana.com/oss/grafana/)
* [Prometheus](https://prometheus.io/)
* [Loki](https://grafana.com/oss/loki/)
* [Tempo](https://grafana.com/oss/tempo/)
* [OpenTelemetry Collector](https://opentelemetry.io/docs/collector/)
* [Victoria Metrics Agent](https://docs.victoriametrics.com/vmagent.html)

Note: this demo project is configured for simplicity and minimal resource usage,
it lacks high-availability, self-monitoring, security and other changes
necessary for production use.

## License

The Unlicense

Note: this project's dependencies are licensed under various different licenses
(including AGPLv3), you must respect those licenses when using this project.

## Author Information

John Freeman

GantSign Ltd.
Company No. 06109112 (registered in England)
