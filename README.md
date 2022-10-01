# hw1_ansible

ubuntu@ip-172-31xx: ~/Ansible/sites$ ansible -i inventory servers -m ping 
ubuntu@ip-172-31xx: ~/Ansible/sites$ ansible-playbook -v -i inventory nginx.yml
ubuntu@ip-172-31xx: ~/Ansible/sites$ ansible-playbook -i inventory undeploy_nginx.yml 
