**Creating homelab Git Repo**
https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository
Ran

# cd ~/NBA-Lab
# git init

Verified git repository created

# ls -a

The .git file is there

# git commit -m "First Commit"

First git commit that has been pushed for this lab
**Installing Podman and Ansible**

https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/10/html/building_running_and_managing_containers/introduction-to-containers#installing-container-tools

Aready registered with RedHat account

# subscription-manager register

# dnf install container-tools

# dnf install podman-docker

Podman is now installed

Verified with

# podamn -v

podman version 5.8.2

https://docs.redhat.com/en/documentation/red_hat_ansible_inside/1.1/html-single/red_hat_ansible_inside_installation_guide/index#individual_rhsm

# sudo dnf install ansible-core

Ansible installed

Verified with

# ansible -v

ansible [core 2.16.16]
  config file = /etc/ansible/ansible.cfg
  configured module search path = ['/home/helloimgucci/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python3.12/site-packages/ansible
  ansible collection location = /home/helloimgucci/.ansible/collections:/usr/share/ansible/collections
  executable location = /usr/bin/ansible
  python version = 3.12.14 (main, Aug 13 2026, 00:00:00) [GCC 14.3.1 20251022 (Red Hat 14.3.1-4)] (/usr/bin/python3)
  jinja version = 3.1.6
  libyaml = True
