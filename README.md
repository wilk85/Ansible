# Ansible
Ansible scripts


script: ** cp_adm_conf **
	copying file from /etc/kuberenetes/admin.conf to your local /home/$user/.kube/config 

script: ** create_user **
	creating user, home directory, .ssh/ directory, ssh-key, adding user to groups as : sudo and root, adding ssh-key to your newly created .ssh/ directory as
	authorized_keys with your username
