ntpdate - Ansible Role
=========

Ansible Role for ntpdate

Installation
--------------

Add requirements your Ansible Playbook `roles/requirements.yaml`

    - src: https://github.com/devopsguild/ansible-role-ntpdate.git
      name: ntpdate
      scm: git
      version: main

Run

    ansible-galaxy install -r roles/requirements.yaml

Variables
--------------

    timezone: Europe/Paris
    ntpdate_server: pool.ntp.org
