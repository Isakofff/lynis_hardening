- Install Ansible first: `apt install ansible`
- Install community.general: `ansible-galaxy collection install community.general`
- Install ansible.posix: `ansible-galaxy collection install ansible.posix`
- For quick debug of new changes: `rsync -rtvh --progress --delete ./lynis_hardening/ ubuntu@43.157.8.205:~/lynis_hardening`
- Run Ansible playbook: `ansible-playbook -i hosts run.yaml`

