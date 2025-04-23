# ansible-add-user
Ansible playbook to add ssh users to Linux and give them 'sudo' access.

Note: Put public user keys in 'dev' directory.
# Usage
$ ansible-playbook add-user.yaml

  What is the username?: joe-user <br />
  Key name?: joe-user  (No need to put .pub extension) <br />
  hostnames: dev-000:dev-111:dev-222 (Use a ':' between hostnames if you're adding to more than one machine.) <br />

  joe-user added.
  
# Update existing user's key.
Run 'update-pkey.yaml'
