ansible-galaxy.ubuntu.docker
================================

```
sudo ansible-playbook -i "localhost," --connection=local --sudo -vvvv run.yml
```

```
ansible-playbook -k -K --become-method sudo --become-user root -i "192.168.1.1," run.yml
```

```
ansible-playbook --ask-pass --become-method sudo --become-user root --ask-become-pass  -i "192.168.1.1," --extra-vars 'docker_compose_version=1.25.0' run.yml
```

