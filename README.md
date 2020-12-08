# Ansible

Para utilizarlo es necesario tener instalado ansible

sudo apt install ansible

Seguido recomiendo crear un fichero con los host con la siguiente extructura
[g_de_host]
x.x.x.x ansible_user=Usuario ansible_become_pass=xxxxxxx

# Intrupciones:

anisble-playbook -i <fichero_host> *.yml
