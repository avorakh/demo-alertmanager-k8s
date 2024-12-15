# demo-alertmanager-k8s

## Install Grafana

Please use the description to install and configure Grafana (including SMTP settings) [Link](https://github.com/avorakh/demo-grafana-k8s/tree/dev-task9)

## Create a Email Contact point
Please follow the documentation using Documentation. - [Link](https://grafana.com/docs/grafana/latest/alerting/configure-notifications/manage-contact-points/integrations/configure-email/#procedure)


## Import a Dashboard

The project contains the dashboard file and this file can be imported. - [Link](K8S claster-dashboard.json)

Import dashboards using Documentation. - [Link](https://grafana.com/docs/grafana/latest/dashboards/build-dashboards/import-dashboards/)

## Create alert rules from panels

Create the alert rules below to follow the Documentation. - [Link](https://grafana.com/docs/grafana/latest/alerting/alerting-rules/link-alert-rules-to-panels/#:~:text=Create%20alert%20rules%20from%20panels&text=Navigate%20to%20a%20dashboard%20in,New%20alert%20rule.)
- High CPU utilization on any node of the cluster.
- Lack of RAM capacity on any node of the cluster.
> - Please set IS ABOVE 80 ot have 80% alert limit.  
> - Set evaluation behavior - Pending period should be 1-5 minutes.
> - Select the created Contact point.
> - Save the alert rule.