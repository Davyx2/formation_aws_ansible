# ansible-project

This projexct contains all asible roles create by galaxy. 
It allow to

1. Create an user to remote Host 
2. Install  ***Docker*** to a remote host
3. Install ***docker-compose*** to a remote host
4. Install **gitlab-runner** 
5. Restart your before configure gitlab-runner to another server in a few minuite

1. RUN playbook

# generate a key pair or using (username/password)
if you want to genearate a key use 
* cd repo/ssh
* ssh-keygen -t rsa -b 4096 
* set inyour inventory file and run playbook

# Running playbook

ansible-playbook -i inventory  playbook.yml
