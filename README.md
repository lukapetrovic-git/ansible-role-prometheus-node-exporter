# Ansible Role for Prometheus Node Exporter
Ansible Prometheus Node Exporter role for Ubuntu
# Requirements
No special requirements, note that this role requires root access, so either run with a global become: yes, or invoke the role in your playbook.

# Role Variables
Role variables are listed below:
```
prometheus_server: [IP address or FQDN of your Prometheus Server]
node_exporter_url: [Node exporter download URL]
```
