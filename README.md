# Ansible Desktop 
I use Ansible to keep my Linux installation reproducible.

## Usage
- Running everything: `ansible-playbook local.yaml --ask-become-pass`
- Running a specific tag: `ansible-playbook local.yaml --ask-become-pass --tag apps`
- Listing all tags: `ansible-playbook local.yaml --list-tags`

