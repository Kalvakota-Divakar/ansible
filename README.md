# Ansible Practice

A collection of Ansible playbooks written while learning Ansible from the basics like variables and loops to real tasks like error handling and idempotency.

---

## Quick Concepts

**What is Ansible?**
A tool that lets you automate tasks on multiple servers at once like installing software, changing settings, or restarting services without logging into each server manually.

**What is a Playbook?**
A YAML file where you write down what you want Ansible to do. For example, "install Nginx on all servers" or "create a new user". Ansible reads the playbook and runs those tasks automatically.

**What is an Inventory?**
A file that lists all the servers you want Ansible to connect to. You group them by role (like web servers, database servers) and Ansible knows where to run your playbooks.

---

## What's Inside

| File | What it does |
|---|---|
| `01-playbook.yaml` | First playbook — basic task execution |
| `02-playbook.yaml` | Running tasks on remote servers |
| `03-playbook.yaml` | More playbook examples |
| `04 to 09-vars.yaml` | Working with variables |
| `10-vars-preference.yaml` | How Ansible picks which variable to use |
| `11-data-types.yaml` | Strings, numbers, lists, and dictionaries |
| `12 to 14-conditions.yaml` | Running tasks only when certain conditions are met |
| `15-shell-command.yaml` | Running shell commands from a playbook |
| `16 to 18-loops.yaml` | Repeating tasks using loops |
| `19-filters.yaml` | Transforming data with filters |
| `20-error-handling.yaml` | Handling failures gracefully |
| `21-idempotenet.yaml` | Making sure tasks don't repeat if already done |
| `inventory.ini` | List of servers Ansible connects to |
| `ansible_facts.json` | System info collected from servers |
| `students.yaml / .json / .xml` | Sample data files used in playbook examples |
| `course.yaml` | Course-related playbook examples |

---

## How to Run

```bash
git clone https://github.com/Kalvakota-Divakar/ansible.git
cd ansible

# Run any playbook against your inventory
ansible-playbook -i inventory.ini 01-playbook.yaml
```

---

## Requirements

- Ansible installed
- At least one Linux server to connect to (or use localhost)

---

## Author

**Kalvakota Divakar**
- GitHub: https://github.com/Kalvakota-Divakar
- LinkedIn: https://www.linkedin.com/in/kalvakota-divakar/

---

## License

MIT
