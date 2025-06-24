# Zenth Monitoring Server

**Zenth Monitoring Server** is an open-source, scalable monitoring and alerting platform developed by Sky Genesis Enterprise for the Zenth Cloud ecosystem. It provides real-time health checks, metrics collection, and alert management across all Zenth services.

## 📊 Features

- ✅ Collects metrics from all Zenth components (servers, APIs, network)
- ✅ Supports Prometheus-compatible scraping and exporters
- ✅ Customizable alerting rules and notifications
- ✅ Dashboards with Grafana integration
- ✅ Service uptime and SLA tracking
- ✅ Integration with `status-server` for public status pages
- ✅ Scalable and containerized architecture

## 📦 Part of the Zenth Cloud Stack

Zenth Monitoring Server integrates closely with:

- `status-server` – Public status and incident management
- `api-server` – Metrics API and event orchestration
- `vpn-server`, `firewall-server`, `dns-server`, `dhcp-server` – Infrastructure monitoring
- `mail-server`, `sip-server` – Communications service monitoring
- `panel-server` – Dashboard and admin interface

## 🛠️ Technology

- Based on Proxmox, with custom extensions and exporters
- Alertmanager for notification management
- Grafana for visualization
- Written in Go for performance and scalability

## 📖 Documentation

Full installation, configuration, and usage documentation is available in `/docs` or on [Documentations](https://docs.zenthcloud.com).

## 🛡️ License

Zenth Monitoring Server is licensed under the **GNU Affero General Public License v3 (AGPLv3)**. See the `LICENSE` file for details.

---

Contributions and feedback are welcome at [github.com/zenthcloud](https://github.com/zenthcloud).
