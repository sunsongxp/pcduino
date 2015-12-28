ansible-galaxy install -r requirements.yml -p roles
ansible-playbook -i inventory.pcduino main.yml -b --become-method=sudo
