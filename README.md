# ansible-add-user
Ansible playbook to add ssh users to Linux

Note: Create a 'keys' subdirectory to hold users public keys.
# Usage
$ ansible-playbook add-user.yaml

  What is the username?: joe-user
  Key name?: joe  (No need to put .pub extension)
  hostnames: dev-000:dev-111:dev-222 (Use a ':' between hostnames if you're adding to more than one machine.)

  joe user added.
  
