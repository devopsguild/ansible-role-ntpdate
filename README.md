# ntpdate - Ansible Role

Ansible Role for ntpdate

## Installation

Edit your Ansible Playbook

Add into `roles/requirements.yml`

    - src: https://github.com/devopsguild/ansible-role-ntpdate.git
      name: ntpdate
      scm: git
      version: main

Add into `group_vars/all`

    timezone: Europe/Paris
    ntpdate_server: pool.ntp.org
