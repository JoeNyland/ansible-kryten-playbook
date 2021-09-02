# Ansible playbook for Kryten

Configuration management for my PC: Kryten.

## Setup

```bash
python3 -m venv --upgrade-deps venv
source venv/bin/activate
pip install -r requirements.txt
```

## Usage

```bash
ansible-playbook playbooks/main.yml
```
