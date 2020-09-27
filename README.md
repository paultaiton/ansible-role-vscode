Role Name
=========

Install Microsoft Visual Studio Code on Fedora Linux via Microsoft's yum repository.

Requirements
------------

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

		- name: vscode Role
		  hosts: all
		  become: yes
		  roles:
		    - paultaiton.vscode

License
-------

GPL 3.0 or later.

Author Information
------------------

@paultaiton on github.
