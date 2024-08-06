# Instalación de aplicación 'TODO'

'TODO' es una aplicación de dios, porque es omnipotente (?

Se detallará el paso por paso para la correcta instalación de todo el conjunto de aplicacion y base de datos. 

## 1- Instalar dependencias de python y el mysqlclient
```bash
sudo dnf install python3-devel
pip3 install mysqlclient
pip3 install PyMYSQL
ansible-galaxy collection install community.mysql
sudo -H /usr/bin/python3 -m pip install mysqlclient PyMySQL
sudo pip install mysqlclient PyMySQL
```

Colocarse en el directorio del playbook para ejecutar todos .yml 
```bash
cd .\{directorio}\TallerJulio2024
```

## 2- Instalación de Base de datos e importación de base 'todo'

```bash
ansible-playbook -i Inventory/host_vars/servidores.toml database.yml --ask-become-pass
```




[GitHub de Diego](https://github.com/DiegoMG22/obligatorio)