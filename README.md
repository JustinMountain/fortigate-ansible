# fortigate-ansible

Standing up FortiGate 50E devices with Ansible 

## Starting Point

Working on a device at `192.168.1.147` with a subnet of `192.168.3.0/24`.

## TODO

1. Double check static routes per current format
1. Complete Firewall Policy per current strategy
1. Take screenshots for comparison
1. Run plays to see if tunnel will come up and setup looks the same
1. Abstract out some details to make it repeatable to both devices
1. Run plays on both devices

## Variables

1. `/roles/role_name/defaults/main.yml` for the most common settings that users might want to override.
1. `/inventory/group_vars/group.yml` for group-specific settings.
1. `/inventory/host_vars/host.yml` for host-specific settings.
1. `/playbooks/play/group_vars/play.yml` for playbook-specific settings.
1. Variables passed with `-e` in the CLI.

Use Ansible Vault for sensitive data.

Keep variable naming consistent and use prefixes to avoid conflicts.
