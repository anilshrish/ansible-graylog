### Run playbook:
```
# install dependencies
ansible-galaxy install -r requirements.yml
ansible-playbook -i inventory site.yml --limit graylog2_servers
```