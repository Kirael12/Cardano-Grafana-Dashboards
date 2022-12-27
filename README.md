# FRADA Grafana Dashboards

Here are my Grafana Dashboards i use to monitor my Cardano stake pool nodes.

# Pre-requisites

I use the following setup :

- 1 dedicated Monitoring Node withe Grafana, Prometheus and Loki installed. It is not mandatory to have 1 dedicated server for monitoring, but i highly recommend it (for ressources, and security reasons)
- Prometheus Node Exporter installed on every node i monitor (relays + block producer)
- Promtail installed on every node i monitor (relays + block producer)

To have a clean Grafana and Prometheus installation you can follow this guide on Cardano Developper Portal :

https://developers.cardano.org/docs/stake-pool-course/handbook/grafana-dashboard-tutorial

To have your stake pool nodes logs on your Grafana Server with Loki and Promtail, follow this guide on Cardano Developper Portal :

https://developers.cardano.org/docs/stake-pool-course/handbook/grafana-loki

# Grafana Server Logs

This dashboard displays logs from my Relays and Block Producers.

- Cardano Logs : leadership checks, block forged, chain extended etc... from BP and Relays

- Security Logs : Firewalling UFW logs and Fail2Ban logs (from my Monitoring Nodes, and Cardano Nodes)

![Capture d’écran 2022-12-27 à 14 19 44](https://user-images.githubusercontent.com/113426048/209678276-40702f7e-5dce-4b8e-9253-7851eceda726.png)

![Capture d’écran 2022-12-27 à 14 19 35](https://user-images.githubusercontent.com/113426048/209678258-2d46430a-9041-4893-a112-4669963d3aa4.png)

![Capture d’écran 2022-12-27 à 14 20 07](https://user-images.githubusercontent.com/113426048/209678320-9436e890-942c-4b87-84fc-4c13484ee04a.png)

# Grafana Main Dashboard 

(soon)
