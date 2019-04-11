# macOS Provisioning

## Prerequisites

* [Ansible](http://docs.ansible.com/ansible/intro_installation.html)
* [Git](http://git-scm.com/downloads)

## Usage

Install the dependencies:

```
ansible-galaxy install -r requirements.yml
```

Run all the tasks:

```bash
ansible-playbook main.yml
```

Run tasks with a specific tag:

```bash
ansible-playbook main.yml -t <tag>
```
