# python3-gce
gce3.py - the Python 3 version of the Google Cloud Engine's Ansible Inventory Plugin.

## Github Repository
Github repository of gce3.py: https://github.com/Asher256/python3-gce

## What is gce3.py?
gce3.py is an Ansible inventory plugin that can automatically suck down
all of your Google Cloud Engine instances into Ansible Dynamic Inventory,
and create groups by tag and other properties.

gce3.py is a modified version (by Asher256 <asher256@gmail.com>) of the
original gce.py created by Google, to make it compatible with Python 3.

A pull request was sent to make gce3.py part of Ansible:
https://github.com/ansible/ansible/pull/26032

## How to use gce3.py?
To use gce3.py as a dynamic inventory, I recommend you to read:
http://docs.ansible.com/ansible/guide_gce.html

The original version (gce.py, the Python 2 version) can be found in
Ansible's official repository:
https://github.com/ansible/ansible/blob/devel/contrib/inventory/gce.py

