Molecule Example
=========

A simple Ansible role that installs wget as a way to demo Molecule.

Requirements
------------

To run molecule tests you will need the following setup:

- Python 2.7
- Pip
- Docker
- Ansible

Then run:

```
pip install docker
pip install molecule --pre
```

Testing
--------------

- ```molecule test``` will run everything (Create, Idempotence, Lint, Verify)
- ```molecule lint``` will run yamllint, flake8 and ansible-lint
- ```molecule check``` will dry run Ansible role

You can also run ```molecule --help``` to see the other avaliable methods.
