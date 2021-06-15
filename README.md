Role Name
=========

Sets up Apache ActiveMQ from binary tgz.

Role Variables
--------------

Check defaults/main for variables that can be adjusted. Especially user,
path and version,

Example Playbook
----------------

    ---
    - hosts: all

      roles:
        - silviuvulcan.activemq
              activemq_version: 5.15.13
              activemq_install_path: /opt
              activemq_user: activemq
              activemq_group: activemq
              activemq_config_template: activemq.xml.j2

License
-------

(BSD, MIT)


Author Information
------------------

https://github.com/silviuvulcan/ansible-role-activemq/
