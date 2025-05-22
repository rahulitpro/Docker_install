# Docker Install Ansible Project

This project contains Ansible playbooks and related files to automate Docker installation.

## Folder Structure

```
.
├── playbook.yml
├── inventory.ini
├── external_vars.ini
└── README.md
```

## Files Overview

- **playbook.yml**: Main Ansible playbook to orchestrate Docker installation.
- **inventory.ini**: Inventory file specifying the target hosts for Ansible.
- **external_vars.ini**: External variables file for customizing playbook behavior.
- **README.md**: Project documentation and usage instructions.

## Usage

1. Update the `inventory.ini` file with your target hosts.
2. Run the playbook:

     ```sh
     ansible-playbook -i inventory.ini playbook.yml
     ```

## Requirements

- Ansible installed on your control machine.
- SSH access to target hosts.

## License

MIT
