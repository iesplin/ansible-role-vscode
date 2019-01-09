ansible-role-vscode
=========

Ansible role for installing VS Code and extensions

Role Variables
--------------

vscode_user (optional) - User which extensions will be be installed for

vscode_extensions (optional) - List of extensions to install

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: ansible-role-vscode
           vscode_user: bob
           vscode_extensions:
             - ms-python.python
             - ms-vscode.go

License
-------

MIT
