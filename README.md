# Customer Support Ticket Management System  
A customer support ticket management system designed to simulate real-world support workflows using core data structures and a modern web interface.  
This project focuses on **queue-based ticket assignment**, **priority escalation**, and **SLA handling**, inspired by how enterprise support systems operate.  
---  
## 🚀 Features  
- 📥 **Ticket Creation**  
  - Create support tickets with title, description, priority, keywords, and SLA.  
- ⏳ **Queue-Based Assignment**  
  - Normal tickets follow **FIFO queue**.  
  - Urgent tickets are handled using a **priority queue**.  
- ⚠️ **Priority Escalation**  
  - Tickets can be escalated to urgent priority dynamically.  
- ⏱️ **SLA Monitoring**  
  - Tracks elapsed time for each ticket.  
  - Automatically flags SLA breaches.  
- 🔍 **Keyword-Based Search**  
  - Search active tickets using keywords.  
- 👤 **Employee Assignment Simulation**  
  - Tickets are assigned to free employees.  
  - Resolving a ticket frees the employee.  
---  
## Tech Stack  
### Backend Logic  
- **C**  
  - Queues  
  - Priority Queues  
  - Hash Maps  
### Frontend  
- React (Vite)   
- JavaScript  
- CSS  
---  
## 📁 Project Structure  
```text
src/
│
├── components/        # Reusable UI components
├── pages/             # Login and Dashboard pages
├── models/            # Ticket and Employee models
├── services/          # Assignment, SLA, search logic
├── utils/             # Helper functions
└── index.css          # Global styling
