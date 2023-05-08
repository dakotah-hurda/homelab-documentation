# Prometheus
Prometheus is a tool that scrapes data from servers and stores that data in a database. 

It's often used with other services, like [Grafana](../grafana/grafana-overview.md), to populate dashboards.

# Key Notes
Some key characteristics about Prometheus: 

- It uses a ['node-exporter' agent](./node-exporter.md) installed on every server to expose metrics about the server on an open TCP port. This is usually tcp/9100 by default.

- I have configured Prometheus to remotely report its data to my [Grafana](../grafana/grafana-overview.md) server. This allows me to make dashboards from its datasources, and potentially custom configure alerting in the future. 

# Resources

- [DevConnected](https://devconnected.com/complete-node-exporter-mastery-with-prometheus/#a_-_Installing_the_Node_Exporter) - I really liked this guide. Very straightforward. 
- [Official Prometheus Docs](https://prometheus.io/docs/introduction/overview/)