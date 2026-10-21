
# 🌸 TaskWise — Smart Task Management System

**Plan Smarter. Stay Organized. Get Things Done.**

TaskWise is a task management application designed to help users organize their daily activities, manage deadlines, track progress, and improve productivity. It provides a simple and user-friendly interface for students and individuals who want to manage their responsibilities efficiently.
Aside from task management, TaskWise also includes a **journal section with sentiment analysis**, allowing users to record their thoughts and understand their emotions.

---

## Core Features

### 1. User Authentication
- User registration and login
- Secure password hashing
- Account management
- Admin and regular user access

### 2. Task Management (CRUD)
- Create new tasks
- View and organize existing tasks
- Edit task information
- Delete completed or unnecessary tasks
- Set task priorities and deadlines

### 3. Search, Filter, and Sorting
- Search for specific tasks
- Filter tasks by category or status
- Sort tasks for easier organization

### 4. Task Status Tracking
- Monitor pending and completed tasks
- Track daily progress
- Manage upcoming deadlines

### 5. Notifications and Reminders
- Receive reminders about upcoming tasks
- Stay informed about approaching deadlines
- Reduce the chances of missing important activities

### 6. Calendar Integration
- View scheduled tasks in a calendar
- Organize activities according to their deadlines
- Manage daily and upcoming schedules

### 7. Journal with Sentiment Analysis
- Write and save personal journal entries
- Analyze the emotional tone of journal content
- Identify positive, negative, or neutral sentiments
- Support emotional awareness through journaling

### 8. Theme Customization
- Customize the application appearance
- Enjoy a responsive and user-friendly interface
- Navigate through a clean and organized design

### 9. Admin Management
- View registered users
- Ban or unban accounts
- Delete user accounts
- Review system activity logs
---
## Technology Stack
TaskWise uses the following technologies:

| Technology | Purpose |
|------------|---------|
| Python | Main programming language |
| Flet | Desktop application user interface |
| Flask | Web backend framework |
| React | Web frontend interface |
| SQLite | Local database management |
| GitHub | Version control and collaboration |

Additional Python libraries support password security, application functionality, and sentiment analysis.

## System Architecture
TaskWise contains two application implementations: a Flet-based version and a Flask-based web version.
### Flet Application
```text
User (Student / Admin)
         |
         v
    Flet UI Layer
         |
         v
 Application Logic
         |
         v
   Database Layer
         |
         v
    SQLite Database
```
### Flask Web Application
```text
       User
         |
         v
   React Frontend
         |
         v
    Flask Backend
         |
         v
   Data Management
         |
         v
   Database Storage
```
---
## Project Structure
```text
TaskWise/
|
|-- flet_version/
|   |-- app/
|   |-- assets/
|   |-- database/
|   |-- taskwise/
|   |-- tests/
|   |-- requirements.txt
|   |-- README.md
|
|-- flask_version/
|   |-- backend/
|   |-- frontend/
|
|-- .gitignore
```

### Folder Descriptions

- **flet_version/** — Python desktop application using Flet.
- **app/** — Authentication, administration, and supporting application pages.
- **assets/** — Images and other interface resources.
- **database/** — Database connection and operations.
- **taskwise/** — Main TaskWise application components.
- **tests/** — Application tests.
- **flask_version/backend/** — Flask backend implementation.
- **flask_version/frontend/** — Web frontend implementation.
---

## 🚀 Installation and Setup

### Prerequisites

Before running TaskWise, make sure you have:

- Python installed
- Git installed
- Visual Studio Code or another code editor
- Node.js and npm for the web frontend

### Step 1: Clone the Repository

```bash
git clone https://github.com/pau-827/TaskWise.git
```

### Step 2: Navigate to the Flet Version

```bash
cd TaskWise/flet_version
```

### Step 3: Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\activate
```

### Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 5: Run the Application

Launch the application's Python entry-point file using the appropriate command.

For the Flask and React implementation, install and configure the backend and frontend dependencies separately.

---

## Project Objectives
TaskWise aims to:

1. Provide an accessible and organized platform for managing daily tasks.
2. Help users prioritize activities and monitor deadlines.
3. Improve productivity through reminders and progress tracking.
4. Encourage self-reflection through journaling and sentiment analysis.
5. Deliver a simple, responsive, and customizable user experience.
---
## Target Users
TaskWise is designed for:
- **Students** — Managing assignments, academic activities, and deadlines.
- **Individuals** — Organizing personal schedules and daily responsibilities.
- **Administrators** — Managing registered accounts and monitoring system activities.
---
## Future Improvements
Possible future enhancements include:
- Cloud-based data synchronization
- Mobile application support
- Advanced productivity analytics
- Enhanced sentiment analysis
- More customization options
- Improved accessibility and responsive design
---
## Project Status
**Academic Project — Under Development**
TaskWise continues to undergo improvements in interface design, application performance, and user experience.
---
## Repository
**GitHub:** https://github.com/pau-827/TaskWise
---

## 📄 License
**No license has been specified for this repository.**
---
**Made with 💗 by the TaskWise Development Team**
*Making task management easier, one task at a time.*
