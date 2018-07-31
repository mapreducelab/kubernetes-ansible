# Ansible playbooks to create Kubernetes cluster offline.

### Run playbook
```
export ANSIBLE_HOST_KEY_CHECKING=false; ansible-playbook -u aputra -i inventory.ini deploy.yml --extra-vars @vars.yml --ask-pass
```
