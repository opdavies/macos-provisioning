# macOS Provisioning

## Prerequisites

* [Ansible](http://docs.ansible.com/ansible/intro_installation.html)
* [Git](http://git-scm.com/downloads)

## Usage

```
ansible-galaxy install -r requirements.yml
```

```bash
$ ansible-playbook main.yml
```

Run everything.

```bash
$ ansible-playbook main.yml -t <tag>
```

Run a specific tag.
