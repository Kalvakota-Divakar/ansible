# Ansible Practice

A collection of playbooks I created while learning Ansible. It covers the basics and some common tasks you are likely to use in real projects.

---

## What is Ansible?

Ansible helps you automate work on servers. Instead of logging into each server and doing the same thing again and again, you can tell Ansible what to do and it takes care of it for you.

## What is a Playbook?

A playbook is simply a file that contains a list of tasks. For example, you can use it to install software, create users, or restart services.

## What is an Inventory?

An inventory is a list of the servers Ansible should connect to and manage.

---

## What's Inside

| File(s) | What it covers |
|---|---|
| `01-playbook.yaml` – `03-playbook.yaml` | Basic playbook examples |
| `04-vars.yaml` – `09-vars.yaml` | Using variables |
| `10-vars-preference.yaml` | Which variable Ansible chooses when the same variable exists in multiple places |
| `11-data-types.yaml` | Working with strings, numbers, lists, and dictionaries |
| `12-conditions.yaml` – `14-conditions.yaml` | Running tasks only when certain conditions are met |
| `15-shell-command.yaml` | Running shell commands |
| `16-loops.yaml` – `18-loops.yaml` | Repeating tasks using loops |
| `19-filters.yaml` | Changing and formatting data |
| `20-error-handling.yaml` | Dealing with failures |
| `21-idempotency.yaml` | Making sure tasks don't repeat unnecessarily |
| `inventory.ini` | Sample inventory file |
| `ansible_facts.json` | Information collected from servers |
| `students.yaml`, `.json`, `.xml` | Sample data files |
| `course.yaml` | Additional examples |

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/Kalvakota-Divakar/ansible.git
cd ansible
```

Run any playbook:

```bash
ansible-playbook -i inventory.ini 01-playbook.yaml
```

---

## What You'll Need

- Ansible installed
- A Linux machine to practice on, or simply use `localhost`

---

## Author

**Kalvakota Divakar**
- GitHub: https://github.com/Kalvakota-Divakar
- LinkedIn: https://www.linkedin.com/in/kalvakota-divakar/

---

## License

MIT
