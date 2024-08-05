# Instalación de aplicación 'TODO'

'TODO' es una aplicación de dios, porque es omnipotente (?

Se detallará el paso por paso para la correcta instalación de todo el conjunto de aplicacion y base de datos. 

## 1- Instalación de Base de datos e importación de base 'todo'

```bash
ansible-playbook -i Inventory/host_vars/servidores.toml database.yml --ask-become-pass
```


[GitHub de Diego](https://github.com/DiegoMG22/obligatorio)