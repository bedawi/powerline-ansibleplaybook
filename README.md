# Powerline Ansible Playbook

## What is this?

This playbook installs powerline, vim-powerline, and tmux-powerline on computers running Fedora Linux (32). It also configures default settings.

## How to use

First set up your Ansible environment. 

You can run this playbook with this command for example:

```bash
$ ansible-playbook addpowerline.yml -b -K
```

## Further reading

### A really quick introduction into how to get started with ansible: 

NetworkChuck. (2020, May 7). you need to learn Ansible RIGHT NOW!! (Linux Automation). Retrieved July 19, 2020, from https://www.youtube.com/watch?v=5hycyr-8EKs

### Where the settings come from:

Frields, P. W. (2020, January 6). Add power to your terminal with powerline. Retrieved July 19, 2020, from https://fedoramagazine.org/add-power-terminal-powerline/

### Ansible documentation

Red Hat. (2019a). blockinfile – Insert/update/remove a text block surrounded by marker lines — Ansible Documentation. Retrieved July 19, 2020, from https://docs.ansible.com/ansible/latest/modules/blockinfile_module.html

Red Hat. (2019b). dnf – Manages packages with the dnf package manager — Ansible Documentation. Retrieved July 19, 2020, from https://docs.ansible.com/ansible/latest/modules/dnf_module.html