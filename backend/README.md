## Deploy with Ansible
* ``cd backend/ansible``
* ``ansible-playbook universal.yml --extra-vars="target=develop"``
* ``ansible-playbook universal.yml --extra-vars="target=staging"``
* ``ansible-playbook universal.yml --extra-vars="target=production"``
