# Kafka Cluster Setup with Ansible (Kraft Mode)

This playbook sets up a Kafka cluster in Kraft mode (without ZooKeeper) using Ansible.

## Directory Structure

- `inventories/production/hosts.ini`: Inventory file listing the Kafka brokers.
- `roles/kafka/tasks/`: Ansible tasks for installing, configuring, and starting Kafka.
- `roles/kafka/templates/server.properties.j2`: Template for Kafka's server configuration.
- `roles/kafka/files/kafka.service`: Systemd service file for Kafka.
- `site.yml`: Main playbook.

## Usage

1. Define your Kafka brokers in the inventory file (`hosts.ini`).
2. Run the playbook:
   ```bash
   ansible-playbook -i inventories/production/hosts.ini site.yml