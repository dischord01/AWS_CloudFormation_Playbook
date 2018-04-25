# AWS_CloudFormation_Playbook
`AWS_CloudFormation_Playbook` Ansible Playbook.

# Setup


# Usage


# Development 

Use `--vagrant` flag to add a Vagrantfile to the Playbook for local testing.

```
vagrant up
vagrant provision
```
 

When you make changes, run `vagrant provision` to update your vms.

# Run Playbook

`ansible-playbook -i production site.yml`

# Ansible Galaxy

```
ansible-galaxy install -r galaxy.yml
```