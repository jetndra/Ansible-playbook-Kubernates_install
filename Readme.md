command used to install k8s
ansible-playbook -i inventory.ini k8s_install.yaml --extra-vars "ansible_sudo_pass=<paas> username=<username> cnifilepath=<cni file path>" --skip-tags "taints"