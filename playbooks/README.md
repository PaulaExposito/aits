# Playbooks

## Contenidos

* Playbook para crear ovejas Centos8 (1 interfaz, DHCP): [ovejas-centos-8.yaml](ovejas-centos-8.yaml:q)

* Playbook para crear ovejas Debian10 (2 interfaces, DHCP): [ovejas-debian-10-dosInterfaces.yaml]( ovejas-debian-10-dosInterfaces.yaml)

* Playbook para borrar ovejas: [borrar-ovejas.yaml](borrar-ovejas.yaml)

* Playbook instalar Docker: [docker-install-playbook.yml](docker-install-playbook.yml)

Utiliza rol: geerlingguy.docker, 4.1.1

* Primer playbook: [first_playbook.yml](first_playbook.yml)

* Playbook instalar Mongo: [mongo-install-playbook.yml](mongo-install-playbook.yml)

Necesita [mongodb-org-5.0.yml](mongodb-org-5.0.yml) <br>
Rol: lesmyrmidons.mongodb, v1.2.8

* Playbook instalar NGINX: (nginx-install-playbook.yml)[nginx-install-playbook.yml]   (Creo que no está funcional)


## Otros

Ejecutar playbook para instalar Docker:

* ansible-playbook docker-install-playbook.yml -i ./hosts


Ejecutar playbook para crear ovejas (CENTOS):

* ansible-playbook --ask-vault ovejas-centos-8.yaml

<br><br>

Opcion '-i': especificar inventario (default: /etc/ansible/hosts)