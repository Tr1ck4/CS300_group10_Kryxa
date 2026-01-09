# Kryxa – Internet Cafe Management System

Kryxa is a locally hosted application designed to manage internet cafés (cybercafés), inspired by SENET and other LAN center management software.  
With the large number of cybercafés in Vietnam (approximately **45,000** according to *gamek.vn, 23/10/2018*), the need for a reliable and modern management solution is essential.

Kryxa provides a web-based interface running on a local server, optimized for **Windows environments**, and supports both staff (admins) and customers (users).

---

## 🎯 Objectives

- Simplify PC and session management for internet cafés
- Automate billing and sales tracking
- Provide real-time session monitoring for users
- Offer extensible features for future needs (statistics, tournaments, visualization)

---

## 👥 Actors

### Admin
- Café staff
- IT administrators

### User
- Players
- Esports organizations

---

## 🚀 Key Features

### Admin Features
- **PC Management**
  - Create and remove PCs
  - Assign PCs to users through a graphical interface
  - Start, extend, or terminate user sessions
  - Set time limits for sessions

- **Session & Billing**
  - Automatically generate bills when a session ends
  - Manage time-based pricing
  - Extend active sessions

- **Sales & Inventory**
  - Add or remove items for sale (food, drinks, etc.)
  - Track item sales
  - Manage customer billing

- **Statistics & History**
  - View sales history
  - Track PC usage time
  - (Planned) Graphs and data visualization

- **Reporting & Management**
  - Create bug reports
  - (Planned) Create and manage tournaments

---

### User Features
- Buy items (food, drinks, etc.)
- Extend session time
- View remaining session time
- View bill details
- Report issues:
  - Technical issues
  - Service-related issues

---

## 🧱 Tech Stack

### Frontend
**Leads:** An (Layout), Khiem (Logic)
- HTML / CSS
- **TailwindCSS** (CSS framework)
- **Svelte** (Frontend framework)

### Backend
**Lead:** Triet
- **Python**
- **FastAPI**
- **SQLite**
- Swagger (OpenAPI) documentation

### UI/UX Design
**Lead:** Bao
- Figma

### Testing
**Lead:** Minh
- API testing: Postman, curl
- Frontend testing: Rice-based system

---

## 🖥️ Target Environment

- **Operating System:** Windows
- **Architecture:** Local server with web-based frontend

---

## 📅 Project Planning & Timeline

### Phase 1
**13/10/2023 – 20/10/2023**
- Complete PA0
- Tool setup

### Phase 2
**13/10/2023 – 27/10/2023**
- Design data schema
- Define general data interactions
- Self-training

---

## 🎓 Seminars & Training

- **17/10/2023** – Backend Introduction  
  *Python, FastAPI, HTTP requests*

- **20/10/2023** – Frontend Introduction  
  *HTML, CSS, JavaScript, Svelte, TailwindCSS*

---

## 📌 Future Improvements
- Advanced data visualization and analytics
- Tournament management system
- Multi-café support
- Role-based access control
- Improved reporting and monitoring tools

---

## 📄 License
This project is developed for academic and educational purposes.  
License information can be added later.

---

## 🤝 Contributors
- An – Frontend lead, developer
- Khiem – Lead Writer, developer
- Triet – Project Manager, Backend lead, developer
- Bao – UI/UX lead, developer(core backend)
- Minh – QA/QC lead, developer

---

## 📬 Contact
For questions or contributions, please open an issue or contact the project contributors.
