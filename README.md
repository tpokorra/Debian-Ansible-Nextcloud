Purpose
=======

Install Nextcloud on a Linux machine or container

Requirements
============

Container with Debian Bookworm

my public SSH key in /root/.ssh/authorized_keys

Run on the container:

    apt install python3 bzip2

Installation
============

Create inventory.yml, similar to inventory-sample.yml

Run on my workstation:

    ansible-playbook -i inventory.yml init.yml
    ansible-playbook -i inventory.yml nextcloud/main.yml
