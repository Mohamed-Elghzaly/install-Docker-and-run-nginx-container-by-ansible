# Ansible Playbook: Install Docker & Run Nginx Container

## 📖 Overview
  This Ansible project automates:
- Installing **Docker** on the target host(s)
- Deploying an **Nginx** container
- Ensuring the container is running and accessible

It uses **Ansible roles** for modular and clean automation.

---

## 🔧 Prerequisites
- **Control machine** with:
  - Ansible installed
- **Target machine(s)** with:
  - Ubuntu OS
  - SSH access & `sudo` privileges

---

## ⚡ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Mohamed-Elghzaly/install-Docker-and-run-nginx-container-by-ansible.git
   cd install-Docker-and-run-nginx-container-by-ansible

2. Update inventory with your target host(s):
  
    ```bash
    [webserver]
    your-server-ip ansible_user=ubuntu ansible_ssh_private_key_file=~/.ssh/id_rsa

3. Run the playbook:

    ```bash
    ansible-playbook -i inventory playbook.yaml

---
## 👤Author

   - **Mohamed Abdullah** : [Github](https://github.com/Mohamed-Elghzaly/)
