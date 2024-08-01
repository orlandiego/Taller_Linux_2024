# Taller Linux 2024
Estos son playbooks de ansible que hacemos para el taller de Servidores Linux

## Instalacion
Instalamos Ansible usando pipx
```
# dnf install python3-pip
$ pip install pipx
$ pipx ensurepath
```

## Uso
```
$ ansible-playbook -i inventario/servidores site.yml
```
## License
MIT
