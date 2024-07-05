# PLAYBOOK

O playbok é o diretório onde a receita que o Ansible utilizará para a instalação dos aplicativos nos servidores/instâncias

## Exemplo

main.yaml

    ---
    - name: Instalar o nginx
    hosts: nginx # Especificados no arquivo hosts do diretório/etc/ansible
    decome: yes # as tarefas vão ser executadas como root
    tasks: 
    - name: Instalar servidor web
        package:
        name: nginx
        state: present

## Executando o playbook

```bash
ansible-playbook -i hosts main.yaml
```

