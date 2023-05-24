# role-ansible-builtin-copy
Ansible Role for ansible.builtin.copy

Synopsis:

The copy module copies a file from the local or remote machine to a location on the remote machine.

Requirements:

|   |   |
|---|---|
| Galaxy Collections | None |
| Operating System | Unix |

Required Vars:

role-ansible-builtin-copy-vars

Parameters:

| Parameter | Tyoe | Usage |
|---|---|---|
| backup | boolean | optional |
| content | string | optional |
| dest | string | required |
| follow | boolean |optional |
| group | string | optional |
| mode | string | optional |
| owner | string | optional |
| remote_src | boolean | optional |
| src | string | optional |
| validate | string | optional |
| become | boolean | optional |
| delegate_to | string | optional |

Reference: https://docs.ansible.com/ansible/latest/collections/ansible/builtin/copy_module.html#ansible-collections-ansible-builtin-copy-module
