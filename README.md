## Docker-Compose file to run InspectIT, InfluxDB and Grafana

InspectIT CMR is a collector which gathers data provided by a Java-based agent, running on a remote server. This provides performance metrics across a number of different parts of the system. InspectIT feeds this data into the InfluxDB database which Grafana then uses to provide human-readable data.

Some tools which help with deployment/configuration:

InfluxDB Studio Client: https://github.com/CymaticLabs/InfluxDBStudio/releases/tag/v0.2.0-beta.1

InspectIT agent: https://github.com/inspectIT/inspectIT/releases

InspectIT Windows management client: https://github.com/inspectIT/inspectIT/releases




