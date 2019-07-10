# Ansible for provider proxmox

## Status
Release version 0.1.0 beta
Now can use only deploy VM from templates
1. Deploy VM is can used
    - full clone from template
    - setting hardware specific
    - Can support automate with cloud-init
    - *** Cannot support clone from non templates
1. Deploy Container(LXC)
    - clone from image template
    - Edit hardware spec
    - Change network config with lxc function
    - *** Original template is only download from proxmox