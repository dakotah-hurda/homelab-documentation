# Prometheus Node Exporters

The Prometheus Node Exporter is an agent that gets installed on any servers you want to monitor. The Prometheus server then runs a routine "scrape" job to collect the statistics exposed by the exporter agent. 

This usually exposes the endpoint on tcp/9100 and hosts a /metrics sub-page. #TODO: #1 How do I secure this API access?

Resources used during install: 

- [DevConnected](https://devconnected.com/complete-node-exporter-mastery-with-prometheus/#a_-_Installing_the_Node_Exporter) - I really liked this guide. Very straightforward. 
- [Official Prometheus Docs](https://prometheus.io/docs/guides/node-exporter/)