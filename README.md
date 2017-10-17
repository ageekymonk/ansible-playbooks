# Ansible Playbooks
This repository contains all the roles and playbooks. Ansible playbooks are run during
1. Building an image (with packer)
2. Running the image

So there is both build time as well as run time labels.

## Playbooks

## Roles
### Common
This role is to configure the server with basic tools and configs. As part of this we install following tools
    - bind-utils
    - collectd
    - git
    - jq
    - lsof
    - make
    - nc
    - ncdu
    - ngrep
    - socat
    - strace
    - the\_silver\_searcher
    - tmux
    - traceroute
    - tree
    - unzip

### Security Hardening

### Rancher Server
