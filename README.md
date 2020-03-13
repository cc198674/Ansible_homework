# Ansible_homework
 Use ansible deploy aws ec2 and windows server

1.update the 'hosts' and './roles/windows/vars/main.yml'
2.place your pair key under ansible folder
3.run ansbile-playbook -i hosts win.yml       for windows deployment
4.run ansible-playbook -i hosts test.yml -b    for aws deployment
