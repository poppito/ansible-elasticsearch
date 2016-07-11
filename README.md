# ansible-elasticsearch

Ansible playbook for Elasticsearch data node installables.

You will need to ensure you can ssh to the target machine using key-exchanges (not username/password). Basically you need a private key on your host machine (running ansible) and a public key (from the same pair) uploaded to the target machine. A good guide can be found at:

https://www.digitalocean.com/community/tutorials/how-to-configure-ssh-key-based-authentication-on-a-linux-server

*** To run the playbook ***

Run the playbook by running (without sudo):

ansible-playbook pb.yml

OR

Run the playbook by running (with sudo): 
ansible-playbook -s pb.yml

