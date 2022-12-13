# mes-ansible

> criar arquivo de hosts

#### listar hosts

```shell
ansible-inventory -i hosts --list
```

#### executar o playbook

```shell
ansible-playbook cfg-copy.yml  -i hosts
ansible-playbook main.yml  -i hosts
```
