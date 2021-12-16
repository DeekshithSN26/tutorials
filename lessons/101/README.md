# Terraform Ansible Integration: GCP Example

[YouTube Tutorial]()

## Prerequisites
Ansible
command -v ansible-playbook
Terraform
command -v terraform

<!-- ssh-keygen -t rsa -f ~/.ssh/ansbile -C ansible -b 2048 -->
ssh-keygen -t ed25519 -f ~/.ssh/ansbile_ed25519 -C ansible

us-central1
different playbooks

ssh -i ~/.ssh/ansbile ansible@34.136.25.166

Cloud DNS API has not been used in project

transfer dns zone to google domains


















## Clean Up

rm ~/.ssh/ansbile*
