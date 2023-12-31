## Run playbook with host file
ansible-playbook longhorn_install.yml -i inventory/k3s_cluster_01/hosts.ini

## Deploy k3s
ansible-playbook site.yml -i inventory/k3s_cluster_01/hosts.ini