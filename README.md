# isu-ansible

## Example Usage

```sh
ansible-playbook -i ./hosts.yml ./app.yml
```


adhoc

```sh
ansible all -i ansible/hosts.yml -b -m ansible.builtin.command -a "top"
```
