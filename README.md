# ak-clean-archi-base-ansible

Exemple Architecture basique et propre pour les projets ansible
```bash
ansible-project/
├── inventory
├── playbook.yml
├── variables/
│   └── var.yml
└── roles/
    └── common/
        ├── defaults/
        │   └── main.yml
        ├── tasks/
        │   ├── apt.yml
        │   ├── yum.yml
        │   ├── task1.yml
        │   ├── task2.yml 
        │   └── main.yml
        └── vars/
            ├── Debian.yml
            └── RedHat.yml
```
