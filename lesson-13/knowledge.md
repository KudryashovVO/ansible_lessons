group_vars
  all
   - "ansible_user : ec2-user"

  us-west-1
   - "ansible_private_key_file = /home/...."



command:

  chmod +x ec2.ry  
  ./ec2.ry --list --resfresh-cache
  ansible-playbook -i ec2.py all playbook.yml
