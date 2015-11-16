# macbook-provisioning

## Prerequisites

* [Ansible](http://docs.ansible.com/ansible/intro_installation.html)
* [Git](http://git-scm.com/downloads)

## Usage

```bash
$ ansible-playbook playbook.yml -K
```

Run everything.

```bash
$ ansible-playbook playbook.yml -K -t <tag>
```

Run a specific tag.
