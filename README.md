# Managed-Hashed-password-and-remote-public-key-for-user-in-Ansible-worker

Using the authorized_key module you can deploy your public key to the remote_user account on all managed hosts.
You need to create and run this [playbook](https://github.com/Hossam-ElHety/Managed-Hashed-password-and-remote-public-key-for-user-in-Ansible-worker/blob/main/Public-key.yml)

## Prerequisites 
This module is part of the ansible.posix collection (version 1.5.4).
You might already have this collection installed if you are using the ansible package. It is not included in ansible-core. To check whether it is installed, run ansible-galaxy collection list.
To install it, use:

        ansible-galaxy collection install ansible.posix.
To use it in a playbook, specify: ansible.posix.authorized_key.

- "Key" parameter is used with lookup to search for public key file path
