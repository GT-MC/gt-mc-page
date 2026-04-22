You are an expert fullstack developer.

Your task is to upgrade and expand an existing Minecraft server website project into a complete, production-ready platform.

IMPORTANT:

* The user already has an existing website (provided as a ZIP project)
* You must analyze, reuse, and improve the existing structure, NOT replace it completely
* Preserve existing systems like team members, layout, and design where possible
* Extend the system with new features and better architecture

---

# TECH STACK

* PHP (structured, preferably MVC or modular architecture)
* MySQL (all persistent data)
* HTML, CSS, JavaScript (modern UI)
* Optional: AJAX for dynamic updates

---

# CORE SYSTEM IMPROVEMENTS

## 1. Database & Config

* Create a central config.php file for database connection
* Move all database credentials into config
* Use PDO with prepared statements
* Design a clean relational database schema

---

## 2. User & Team System

* Keep existing team members from the old project

* Build a full user system:

  * Register/Login
  * Password hashing (bcrypt)
  * Sessions

* Roles:

  * User
  * Supporter
  * Moderator
  * Admin
  * Owner

* Team dashboard:

  * Manage users
  * Assign roles/ranks
  * View activity

---

## 3. Staff Dashboard (Advanced)

* Overview page (stats, tickets, active chats)
* Manage:

  * Tickets
  * Reports
  * Bug reports
  * Ideas
* Permission-based access system

---

## 4. Shift System (Support Shifts)

* Staff can start/end shifts
* Track:

  * Start time
  * End time
  * Duration
* Show currently active staff
* Store all shift logs

---

# SUPPORT & COMMUNICATION SYSTEMS

## 5. Ticket System (FULL)

* Users can create tickets with categories:

  * General Support
  * Report Player
  * Bug Report
  * Idea / Suggestion
  * Feedback

* Features:

  * Status (open, closed, in progress)
  * Assign to staff
  * Chat inside ticket
  * File attachments (optional)

---

## 6. Live Support Chat

* Real-time or near real-time chat
* User ↔ Staff communication
* Show online staff
* Store chat logs

---

## 7. AI Support

* AI chatbot for instant support
* If AI cannot solve → escalate to ticket or staff
* Integrate into support page

---

# COMMUNITY FEATURES

## 8. Team Rating System

* Users can rate staff members
* Rating system (1–5 stars)
* Optional comment
* Store ratings in database
* Show average rating per staff member

---

## 9. Feedback System

* Users can submit general feedback
* Admins can review and respond
* Feedback categories

---

## 10. Report System

* Report players or users
* Fields:

  * Report reason
  * Description
  * Evidence (optional)
* Staff can review, accept, reject

---

## 11. Bug Report System

* Dedicated bug report form
* Track:

  * Status
  * Priority
* Admin view for bug management

---

## 12. Idea / Suggestion System

* Users submit ideas
* Other users can vote (optional)
* Staff can mark:

  * Accepted
  * Rejected
  * In progress

---

## 13. Wiki System

* Create a simple internal wiki:

  * Pages (editable by admins)
  * Categories
  * Rich text content
* Used for:

  * Server rules
  * Guides
  * FAQs

---

# ADMIN PANEL

## 14. Full Admin Control Panel

* Manage:

  * Users
  * Roles
  * Tickets
  * Reports
  * Bugs
  * Ideas
  * Feedback
* Logs:

  * Who did what (activity log)

---

# FRONTEND

## 15. UI/UX

* Keep style of existing website but improve it
* Modern gaming design (Minecraft-themed)
* Responsive (mobile-friendly)
* Dashboard layout (sidebar + content)

---

# SECURITY

## 16. Security Features

* CSRF protection
* XSS prevention
* Input validation
* Secure authentication
* Role-based access control

---

# OUTPUT REQUIREMENTS

* Provide full file structure
* Include:

  * All PHP files
  * SQL schema (CREATE TABLE)
  * config.php example
* Clearly comment code
* Explain:

  * How to install
  * How to run locally
  * How to connect database

---

# GOAL

Transform the existing Minecraft server website into a complete, scalable, all-in-one platform with professional systems for support, team management, and community interaction.

The result should feel like a real SaaS-level web application.
