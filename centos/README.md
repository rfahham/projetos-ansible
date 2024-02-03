# centos

## Saber se os hosts estão ativos

```bash
ansible distros -a "uptime"
```

## Executando modificações nos hosts

```bash
ansible distros -a "apt-get update"
```
