### requirements
- vagrant: `^2.2.18`
- ansible: `^2.9.6`

### how to start
```shell
vagrant up && \
ansible-playbook \
ansible/scripts/provisioning.yml \
-i ansible/hosts
```