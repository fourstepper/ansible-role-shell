ansible-role-terminal
=========

This role installs and configures a ZSH with p10k setup on a given machine

Requirements
------------

This role assumes you have a `.zshrc` and, alternatively, a `p10k.zsh` ready to go

Place those files as `zshrc` and `p10k.zsh` in the templates/ directory

If you only have a `.zshrc` and want to run `p10k configure` afterwards, just skip the `p10k.zsh` file

Role Variables
--------------

The needed terminal_packages are defined in the defaults/main.yml file.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: all
      roles:
         - role: ansible-role-terminal

License
-------

MIT
