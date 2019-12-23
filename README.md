# Playbook for the IoTree Led-Service

## Getting Started

After cloning it's as easy as:

1. Install Ansible.
2. Install a fresh linux on a Pi, enable ssh-access and update the `inventory.yml` according to the credentials you set up. Better not use the default credentials.
3. Start the playbook with `ansible-playbook -i inventory playbook.yml`.
4. The first setup will fail during the node-red setup (since it's not in the playbook - feel free to add). Follow [these](https://nodered.org/docs/getting-started/raspberrypi) instructions to install node-red and re-run the playbook.

Enjoy.
