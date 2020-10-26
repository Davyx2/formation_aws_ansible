Install Docker Compose
=========
Ce role permet d'installer le et d'attribuer des droit s pour l'execution de docker_compose sur un serveur ubuntu

Requirements
------------

Arch: ubuntu <= 18.04
Package: curl

Role Variables
--------------

Une seule variables a été encrypté avec l'algorithme à clé sysmétrique AES 256.
Executer ce role en ajoutant l'option --ask-vault-pass
Password: 1234

Dependencies
------------

Pas de dependance

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: server
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------
 David SEIDOU Cybersecurity Ananlyst & DevOps Junior 
