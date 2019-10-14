# bootstrap_server_ansible_playbook

Run for password hash: mkpasswd --method=sha-512

The following steps must be performed:
1) Name hosts.example in hosts and customize the server
2) Create a password hash for the new user with: mkpasswd --method=sha-512
3) Name group_vars/servers.example in group_vars/servers and customize the entries
4) Run the Playbook with ./bootstrap_servers.yml or ansible-playbook bootstrap_servers.yml