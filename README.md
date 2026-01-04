# osTicket Helpdesk Ticketing System (IT Support Portfolio Project)

## Project Overview
This project demonstrates the installation, configuration, and administration of an **osTicket helpdesk ticketing system** in a **virtualized Linux environment**.  
The goal was to simulate a **real-world IT Support / Helpdesk workflow**, including ticket creation, escalation, SLA management, and resolution.

The project was built as hands-on practice for an **entry-level IT Support Engineer role**.

---

## Lab Environment
- **Virtualization:** VMware Workstation 17 Player
- **Guest OS:** Ubuntu Desktop 22.04 LTS
- **Web Server:** Apache
- **Database:** MySQL
- **Scripting Language:** PHP
- **Ticketing System:** osTicket



---

## Installation Summary
1. Deployed Ubuntu Desktop in VMware
2. Installed LAMP stack (Apache, MySQL, PHP)
3. Downloaded and configured osTicket
4. Created MySQL database and dedicated database user
5. Secured installation by removing setup directory and locking configuration files

---

## Helpdesk Configuration
The helpdesk was configured to reflect a **real enterprise IT environment**:

### Departments
- IT Support
- Networking
- Hardware

### Agents (Support Staff)
- **Level 1 Support:** Handles common issues (password resets, basic troubleshooting)
- **Level 2 Support:** Handles escalated issues (network and advanced problems)

### SLA Plans
- **Critical:** 1 hour response
- **High:** 4 hour response
- **Normal:** 8 hour response

### Help Topics
- Password Reset
- Network Connectivity
- Hardware Issues

---

## Ticket Lifecycle Management
This project demonstrates the **full lifecycle of IT support tickets**:

1. User submits ticket via Client Portal
2. Ticket is routed based on Help Topic
3. Level 1 agent reviews and resolves basic issues
4. Complex issues are escalated to Level 2 support
5. Tickets are resolved and closed with documented responses

Example scenarios handled:
- Password reset (resolved by Level 1)
- Network connectivity issue (escalated to Level 2)

---

## 🛠️ Troubleshooting Performed
During the project, several real-world issues were encountered and resolved:

- Git not installed (`command not found`) → Installed via apt
- Admin authentication errors → Verified account status and reset credentials via MySQL
- Help Topics not appearing → Enabled topics and verified ticket form configuration
- Email validation errors → Used reserved test domain (`example.com`)

---

## 📸 Screenshots
Screenshots included in this repository show:
- Virtual machine setup
- Apache and MySQL running
- Database creation in MySQL shell
- osTicket installation
- Admin and agent dashboards
- Ticket submission, escalation, and resolution

(See `/screenshots` directory)

---

## 🧠 Skills Demonstrated
- IT Helpdesk Operations
- Ticketing Systems (osTicket)
- Incident & Escalation Management
- SLA Configuration
- Linux System Administration
- Virtualization (VMware)
- Troubleshooting & Documentation

---

## 📎 Author
**Aspiring IT Support Engineer**  
Portfolio project created to demonstrate hands-on helpdesk experience.

