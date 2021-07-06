# Basics

```bash
apt install python ansible git
git clone https://github.com/bernisys/ansible-base.git
cd ansible-base
ansible-playbook -i localhost, base-install.yml
```


# hints

```bash
export ANSIBLE_STDOUT_CALLBACK=actionable
ansible-playbook -i hosts base-install.yml 
```

