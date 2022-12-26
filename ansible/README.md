# ansible

Ansible source for setting up my system.

## Requirements

```bash
pacman -S ansible
```

## Steps

1. Install required collections from Ansible Galaxy

```bash
ansible-galaxy install -r requirements.yml
```

2. Run the Ansible playbook

```bash
ansible-playbook -K playbook.yml
```

