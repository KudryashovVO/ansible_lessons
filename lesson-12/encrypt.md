# ansible-vault create mysecret.txt
# ansible-vault view mysecret.txt
# ansible-vault edit mysecret.txt

# ansible-vault rekey mysecret.txt

# ansible-vault encrypt myfile.yml
# ansible-vault decrypt myfile.yml

# ansible-playbook mypb/yml --ask-vault-pass
# ansible-playbook mypb.yml --vault-password-file password.txt

# ansible-vault encrypt_string
# echo -n "secretword" | ansible-vault encrypt_string
