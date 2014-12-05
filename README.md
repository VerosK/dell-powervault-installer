Install Dell PowerVault MD1200
------------------------------

Deell PowerVault 1200 is cheap storage array without web nor CLI
management tool. It has to be managed from Windows or Linux computer.

This playbook downloads ISO with driver and prepares for installation.

*Steps:*

1. Install plain CentOS 7
2. Run playbook 
3. Run last command in playbook manually.
4. Reboot machine
5. Use `SMclient` or `SMcli` to manage the array.
