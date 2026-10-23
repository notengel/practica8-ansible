# Practica 8: Ansible con Docker

1. `docker compose up -d --build`
2. En WSL: `sudo apt install ansible sshpass -y`
3. `ansible all -m ping`
4. `ansible-playbook playbook.yml`
5. Verificar: `ansible all -a "ls /home/itla/app" -b`
