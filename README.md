# Ansible
Ansible scripts - you have to provide hosts file by yourself


script: **cp_adm_conf**
	copying file from /etc/kuberenetes/admin.conf to your local /home/$user/.kube/config 

script: **create_user**
	creating user, home directory, .ssh/ directory, ssh-key, adding user to groups as : sudo and root, adding ssh-key to your newly created .ssh/ directory as
	authorized_keys with your username

script: **multiple_users**
	creating multiple users, adding .ssh/ folder and in it authorized_keys file, you have to add another object into the list, if you want to created another user
