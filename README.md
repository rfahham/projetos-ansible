# Ansible

Ansible é uma ferramenta de TI de código aberto para gerenciar, automatizar, configurar servidores e, implantar aplicativos, a partir de uma localização central. Ele inclui sua própria linguagem declarativa para descrever a configuração do sistema.

[O mínimo que você precisa saber sobre ANSIBLE!](https://www.youtube.com/watch?v=y5eKF_XnGyE)

## Install

[Installing Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#pipx-install)

## Version

```bash
ansible --version
```

## Colections

[collections_using](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html)

## O playbook é a soma de vários "plays"

Criando um playbook.yaml

## Executando o playbook

```bash
ansible-playbook -i hosts playbook.yaml
```

## Verificando acesso

Verifica se a máquina consegue acessar os hosts destinos

```bash
ansible distros -m ping
```

## Inventário

[nginx]
IPs

[docker]
IPs

[nginx:vars]

[docker:vars]
