

### Requirements:
- [Prometheus] and [Node Exporter]
- Grafana


[Prometheus]: https://github.com/prometheus/prometheus/releases/download/v2.16.0/prometheus-2.16.0.linux-amd64.tar.gz

[Node Exporter]: https://github.com/prometheus/node_exporter/releases/download/v0.18.1/node_exporter-0.18.1.linux-amd64.tar.gz


### Monitoring Challenge milestones

- Set up an AWS account
- Set up 3 t2.micro AWS EC2 instances
- Installed Prometheus and Node Exporter: Followed [Digital Ocean article] for steps for installation and configuration
- Installed Grafana and connected it with Prometheus: Steps taken from the [Official Documentation]
- Created a new dashboard with graphs on Grafana

#### Prometheus
- A monitoring and alerting toolkit that captures time-series data in a key-value pair format.
- Prometheus scrapes data through service discovery configurations in prometheus.yml file.

#### Grafana
- Query, visualize, alert on and understand your metrics on any data (in this case the data provided by Prometheus)

#### Node Exporter
- To collect Linux server related metrics and statistics for monitoring
- Requires Prometheus server to be up and running

##### Misc
- Remmina (Referred [article])
	- Get the IP address or host address of the instance
	- Set up a default password for user ubuntu
	- Start RDP connection on Remmina using the IP address or host address


[article]: https://comtechies.com/how-to-set-up-gui-on-amazon-ec2-ubuntu-server.html
[Digital Ocean article]: https://www.digitalocean.com/community/tutorials/how-to-install-prometheus-on-ubuntu-16-04
[Official Documentation]: https://prometheus.io/docs/visualization/grafana/ 
