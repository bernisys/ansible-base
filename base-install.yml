---
  - name: deploy basic software packages
    hosts: localhost
    connection: local
    become: true
    become_user: root

    tasks:

      - name: Install midnight commander
        ansible.builtin.package:
          name: mc
          state: present
