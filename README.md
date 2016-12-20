# macOS Provisioning

## Prerequisites

* [Ansible](http://docs.ansible.com/ansible/intro_installation.html)
* [Git](http://git-scm.com/downloads)

## Usage

```
ansible-galaxy install -r requirements.yml
```

```bash
$ ansible-playbook main.yml -i inventory
```

Run everything.

```bash
$ ansible-playbook main.yml -i inventory -t <tag>
```

Run a specific tag.
