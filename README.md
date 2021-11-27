#  docker-Ansible
dws-ops-002-Ansible

## What is Ansible?

Ansible is yet another tool for managing a large number of servers. With Ansible playbooks, you can create incredibly flexible, automated tasks to run on your data center servers, all from a single point of entry.

## Installing Ansible

Ansible is an agentless automation tool that you install on a control node. From the control node, Ansible manages machines and other devices remotely (by default, over the SSH protocol).

```bash
pip install ansible
```
[Installing ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)


## Usage

```yaml

# source venv activate
source venv/bin/activate

# ls
host.ini  play.yaml  venv

# run ansible playbook
ansible-playbook -i host.ini -b play.yaml
```

## Contributing
Don't hesitate to contribute. In the case of a bug, please file an issue.

## License
[MIT](https://github.com/madrika/docker-ansible/blob/main/LICENSE)
