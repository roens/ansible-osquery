# Ansible Playbook for Installing osquery

- doesn't work on 32 bit machines
- requires sudo access to install package

Install osquery on Ubuntu:
```
sudo ansible-playbook ubuntu.yml
```

Install osquery on Amazon Linux:
```
sudo ansible-playbook ami.yml
```
