# Ansible Automation for App Servers

## Overview
This repository contains Ansible playbooks and inventory files for automating tasks on Ubuntu app servers in the DEEM Data Center.

## Lab 1: Ansible Install Package
- **Inventory File**: `/playbook/inventory`
- **Playbook**: `/playbook/playbook.yml`
- **Task**: Install `httpd` package on app servers.

## Lab 2: Ansible Manage Services
- **Inventory File**: `/ansible/inventory`
- **Playbook**: `/ansible/playbook.yml`
- **Task**: Install `httpd`, start, and enable the service on app servers.

## Lab 3: Creating Soft Links Using Ansible
- **Inventory File**: `/ansible/inventory`
- **Playbook**: `/ansible/playbook11.yml`
- **Task**: Create files and symbolic links on app servers.

## Lab 4: Ansible Unarchive Module
- **Inventory File**: `/ansible/inventory`
- **Playbook**: `/ansible/playbook2.yml`
- **Task**: Unarchive `devops.zip` on app servers.

## Lab 5: Ansible File Module
- **Inventory File**: `playbook/inventory`
- **Playbook**: `playbook/playbook1.yml`
- **Task**: Create `/opt/nfsshare.txt` file on all app servers.

## Lab 6: Using Ansible Conditionals
- **Inventory File**: `/ansible/inventory`
- **Playbook**: `ansible/playbook3.yml`
- **Task**: Copy files to app servers using conditionals.

## Lab 7: Ansible Create Users and Groups
- **Inventory File**: `/playbooks/inventory`
- **User Data**: `/playbooks/data/users.yml`
- **Playbook**: `/playbooks/add_users.yml`
- **Task**: Create users and groups on app server 2.
