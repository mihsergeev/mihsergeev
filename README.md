## Hi, I'm Mihail

Infrastructure and operations engineer, 20+ years with Linux servers. I keep production fleets running and write the tooling around them.

**Day to day:** Debian and Ubuntu, Docker and compose, Ansible across the whole fleet, Kubernetes (k0s, k3s, microk8s, kubeadm) with Flux, nginx and Caddy as front ends, TLS and IP allowlists, systemd units and timers, PostgreSQL, MySQL and ClickHouse, restic backups with retention and restore checks, WireGuard and OpenVPN, GitHub Actions.

**High availability:** keepalived VIPs, PostgreSQL under Patroni, nginx load balancing, failover without downtime.

**Code:** Python (FastAPI), Go for agents, Bash, React and TypeScript for the panels below.

### Panels I build

- [Kervax](https://github.com/mihsergeev/Kervax) - monitoring for sites, servers, containers, databases and backups in one panel. One command brings it up, the agent discovers what runs on each machine.
- [amnezia-control](https://github.com/mihsergeev/amnezia-control) - self-hosted panel for AmneziaWG, OpenVPN-over-Cloak and XRay/REALITY nodes: deploy a node, issue and revoke client configs, traffic and node health, alerts, 2FA.
- [NodeRoost](https://github.com/mihsergeev/NodeRoost) - self-hosted panel for headscale: access grants instead of hand-written HuJSON, device isolation, roles, subnets, per-device exit gateways.
- Sekvyr (in progress) - secrets and environment variables. Values are edited in the web UI, servers and clusters pull them over the API and keep their local `.env` files in sync. The admin UI sits behind a VPN, the machine API is public.

### Open for part-time work

Remote, part-time, infrastructure and operations: servers, deploys, monitoring, backups, incident work, one-off tooling. During working hours I reply straight away and pick the task up the same day.

Telegram: [@ms_sre](https://t.me/ms_sre)
