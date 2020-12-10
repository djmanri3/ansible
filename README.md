# Ansible

Para utilizarlo es necesario tener instalado ansible

sudo apt install ansible

Seguido recomiendo crear un fichero llamado hosts con la siguiente extructura:

[g_de_host]

x.x.x.x ansible_user=Usuario ansible_become_pass=xxxxxxx

# Intrupciones:

anisble-playbook -i hosts *.yml

# Nextcloud

- Descomentar en cont1_nextcloud.yml segun la arquitectura que tengais
- Cambiar hosts: casa en docker+contenedores.yml

# Pydio

- Cambiar rutas de "data" en cont2_pydio.yml
- Asignar una contraseña a root en cont2_pydio.yml
- Cambiar hosts: casa en docker+contenedores.yml
