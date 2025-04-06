# aws_db_ansible_playbooks
Collection of helpful aws db related ansible playbooks


## Tower/AAP/AWX
These are very similar, if not the same as the local playbooks. These are ready to use with Ansible Automation Platform/AWX/Tower and, of course, you will need to create the secrets and variables in those systems for the playbooks to properly execute. If you would like less overhead (and infrastructure), then I would sugget using the "Local" versions of these playbooks and schedule via cronjobs.

## Local
Straight forward playbooks that will require you to setup your inventory files, var files, and encrypt your secrets with Ansible Vault.

