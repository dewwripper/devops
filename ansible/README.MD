ansible -i hosts -m ping nordic
ansible-playbook -vvvv -i hosts playbooks/testing.yaml > bizfly.log
