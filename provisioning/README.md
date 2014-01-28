# Ansible playbook for Storm #
- For delpoy a jar file you can do like this:
```
ansible-playbook -i production playbooks/deploy.yml --extra-vars '{"jar":"address of jarfile", "class_params":"class name and parameters"}'
```
- For kill a topology you can do it like this:
```
ansible-playbook -i production playbooks/stop.yml --extra-vars '{"name":"topology name"}'
```
