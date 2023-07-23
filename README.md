# Ansible Playbook Files

## Quick Setup

1. Install Ansible on your host controller system.
2. Update the inventory file with server IP addresses/FQDNs.
3. Ensure servers are reachable via SSH from the host.
4. Run playbooks using: `ansible-playbook your_playbook.yml -i inventory`.

## Playbooks and Functionalities

| Playbook Name       | Functionality                                     |
|---------------------|---------------------------------------------------|
| `setup.yml`         | Installs docker on Debian servers.                |
| `containers.yml`    | Runs the mentioned containers on the servers.     |

For detailed instructions on how to run the playbooks, further customization, and more advanced features, please refer to the [official Ansible documentation](https://docs.ansible.com/ansible/latest/user_guide/index.html). Happy automating!
