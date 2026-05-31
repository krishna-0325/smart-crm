# 🔷  Personal CRM System

> **Intern ID:** CITS2697  
> **Project Type:** Intermediate Frontend Web Application  
> **Tech Stack:** HTML · CSS · Vanilla JavaScript  
> **Submitted as:** Intern Task Assignment

---

## 📌 Project Overview

**Smart-crm** is a fully functional Personal CRM (Customer Relationship Manager) built as a single-page web application using only HTML, CSS, and JavaScript — no frameworks, no backend, no dependencies beyond Google Fonts.

It is designed to help individuals manage their professional network, track relationships, log follow-up tasks, and visualize contacts across a sales/relationship pipeline — all from the browser, with data persisted via `localStorage`.

---

## ✨ Features

### 🏠 Dashboard
- Live summary stats: Total Contacts, Active Leads, Clients, Open Tasks
- Recent contacts panel
- Upcoming tasks panel
- Auto-updating date display

### 👥 Contacts
- Add, edit, and delete contacts
- Fields: First/Last Name, Email, Phone, Company, Job Title, Status, LinkedIn/Website, Notes
- Real-time search across name, company, and email
- Filter by relationship status (Lead / Prospect / Client / Partner)
- Sort by Name, Recently Added, or Company
- Auto-generated color avatars with initials
- Last contacted timestamp tracking

### 📋 Contact Detail View
- Full profile modal with all contact info
- Activity log (auto-logs profile views)
- Direct edit and delete from detail view
- Clickable website/LinkedIn links

### 📊 Pipeline View
- Kanban-style column layout
- Four stages: **Leads → Prospects → Clients → Partners**
- Contact count per stage
- Click-through to contact detail

### ✅ Tasks
- Add tasks with optional due date and linked contact
- Mark tasks as done / pending
- Filter view: All / Pending / Done
- Delete individual tasks
- Task count badge on sidebar

### 🎨 UI/UX
- Dark theme with custom CSS design system
- Subtle grid background texture
- Smooth animations and hover transitions
- Toast notification system (success / error)
- Responsive layout (mobile-friendly sidebar collapses)
- Keyboard-friendly modal interactions (click outside to close)

---

## 🗂️ Project Structure

```
nexus-crm/
└── index.html       # Complete app — HTML + CSS + JS in one file
└── README.md        # Project documentation
```

> The entire application lives in a single `index.html` file — no build tools, no npm, no server required.

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/nexus-crm.git
   ```
2. Navigate into the folder:
   ```bash
   cd nexus-crm
   ```
3. Open `index.html` in any modern browser:
   ```bash
   # macOS
   open index.html

   # Windows
   start index.html

   # Linux
   xdg-open index.html
   ```

No installation. No build step. No internet connection required after the page loads (fonts need internet on first load).

---


## 💾 Data Persistence

All contact and task data is stored in the browser's `localStorage`. Data persists across page refreshes and browser restarts on the same device. Clearing browser data will reset the app.

Seed data (4 sample contacts + 3 sample tasks) is pre-loaded on first launch to demonstrate the interface.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | App structure and markup |
| CSS3 | Styling, animations, layout (CSS Grid & Flexbox) |
| Vanilla JavaScript (ES6+) | Logic, state management, DOM manipulation |
| localStorage API | Client-side data persistence |
| Google Fonts | Typography (DM Serif Display, DM Mono, Syne) |

---

## 📚 Concepts Demonstrated

- DOM manipulation and dynamic rendering
- CRUD operations (Create, Read, Update, Delete)
- Client-side search and filtering
- State management without a framework
- CSS custom properties (variables) and design systems
- CSS animations and transitions
- Event delegation and modular JS functions
- Responsive design with media queries
- Single Page Application (SPA) routing pattern

---

## 🔮 Possible Future Enhancements

- Export contacts to CSV
- Import contacts from a file
- Cloud sync via Firebase or Supabase
- Email/calendar integration
- Reminders and notifications via the Web Notifications API
- Dark/light theme toggle
- Drag-and-drop pipeline reordering

---

## 👤 Author

**Intern ID:** CITS2697  
**Project:** Personal CRM System  
**Assignment Level:** Intermediate  

---

*This project was built as part of an internship task to demonstrate intermediate proficiency in frontend web development.*
