# **My 1-Week Intensive Ansible Learning Plan**

This is my personal plan to build foundational skills in Ansible within a week. I’ve broken it down into daily objectives and activities to stay focused and make consistent progress.

---

## **Day 1: Introduction to Ansible**
### What I’ll Learn:
- Understand what Ansible is and how it works.
- Learn about Ansible's architecture (control node, target hosts).
- Explore key concepts like agentless design, SSH/WinRM communication, and declarative language.

### What I’ll Do:
1. Read the [official Ansible introduction](https://docs.ansible.com/).
2. Watch an introductory video or tutorial about Ansible basics.
3. Install Ansible on my computer (control node).

---

## **Day 2: Inventory Management**
### What I’ll Learn:
- Understand how Ansible inventory files define hosts.
- Learn how to group hosts for easier management.

### What I’ll Do:
1. Create a simple inventory file with hostnames or IPs.
2. Organize hosts into groups (e.g., `web`, `db`).
3. Test connectivity to the hosts using the `ping` module.

---

## **Day 3: Ad-Hoc Commands and Ansible Modules**
### What I’ll Learn:
- Use ad-hoc commands for quick tasks.
- Understand Ansible modules for configuration management.

### What I’ll Do:
1. Run ad-hoc commands to:
   - Check system uptime (`command` module).
   - Install a package (`yum` or `apt` module).
   - Copy a file to target hosts (`copy` module).
2. Explore the Ansible module documentation and experiment with at least three modules.

---

## **Day 4: Writing My First Playbook**
### What I’ll Learn:
- Understand YAML syntax for writing playbooks.
- Write a playbook to automate tasks.

### What I’ll Do:
1. Create a playbook to:
   - Install a package.
   - Create a file with specific permissions.
   - Start or stop a service (e.g., `nginx` or `httpd`).
2. Run my playbook and verify its results on a target host.

---

## **Day 5: Variables and Handlers**
### What I’ll Learn:
- Use variables to make playbooks flexible.
- Create handlers to manage state changes efficiently.

### What I’ll Do:
1. Add variables to my playbook for:
   - Package names.
   - File paths.
2. Create a handler to restart a service when a configuration file is updated.

---

## **Day 6: Roles and Structuring Playbooks**
### What I’ll Learn:
- Organize my playbooks using roles.
- Understand directory structures and reusable components.

### What I’ll Do:
1. Create a simple role with tasks, templates, and variables.
2. Use the role in a playbook to manage multiple hosts.

---

## **Day 7: Practice and Real-World Scenarios**
### What I’ll Learn:
- Apply what I’ve learned in a practical project.
- Explore Ansible Galaxy for pre-built roles.

### What I’ll Do:
1. **Mini-Project**: Automate web server deployment.
   - Install `nginx` or `httpd`.
   - Deploy a static website.
   - Configure firewall rules.
2. Explore and download a role from [Ansible Galaxy](https://galaxy.ansible.com/) to use in my project.

---

## **My Outcomes After One Week**
By the end of this week, I aim to:
1. Explain Ansible's architecture and core concepts.
2. Manage hosts and groups using inventory files.
3. Execute ad-hoc commands for basic tasks.
4. Write and test my own Ansible playbooks.
5. Use variables, handlers, and roles to organize automation effectively.
6. Apply Ansible to real-world tasks like web server deployment.

---

## **Resources I’ll Use**
- [Ansible Documentation](https://docs.ansible.com/)
- [Ansible for DevOps (Jeff Geerling)](https://www.ansiblefordevops.com/)
- Free Ansible tutorials on YouTube and Udemy.

---

I’m excited to complete this plan and build my Ansible skills step by step!
