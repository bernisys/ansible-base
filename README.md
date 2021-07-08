# hints
```bash
export ANSIBLE_STDOUT_CALLBACK=actionable
```


# Basic installation
```bash
apt install python ansible git
git clone https://github.com/bernisys/ansible-base.git
cd ansible-base
ansible-playbook -i localhost, base-install.yml
```


# user creation and enablement
```bash
useradd -m -s /bin/bash <username>
chage -p 0 <username>
```


