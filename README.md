# grafana-docker
Grafana running in a docker container using docker-compose.

## volumes

Map storage to /var/lib/grafana, in this case a docker volume that was created previously
Map the ini file and use the --config option on the entrypoint to tell grafana to read any overrides from it.

You can install plugins either by using the environment variable or my mapping the plugin directory directly.
