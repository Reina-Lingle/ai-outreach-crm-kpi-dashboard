# outreach_dashboard
A lightweight, client-side CRM and KPI dashboard designed to streamline strategic networking, informational interviews, and follow-up velocity with industry leaders.
Overview
The Outreach CRM & Velocity Hub is a single-page web application (SPA) tailored for researchers, engineers, and professionals conducting high-impact outreach in your ecosystem.
Rather than serving as a passive contact book, this CRM actively drives daily outreach velocity by enforcing structured networking methodologies:
The 3B7 Follow-Up Rule: Automated reminders to nudge after 3 business days or pivot/close out after 7 business days.
The TIARA Framework: Built-in playbook for structuring 20-minute informational interviews (Trends, Insights, Advice, Resources, Assignments).
Weekly Pace Gauges: Target tracking for initial messages sent, interviews scheduled, and 24-hour thank-you notes completed.
Key Features
1. Actionable KPI Dashboard & Velocity Visualizer
   Weekly Pace Gauges: Live progress bars tracking target outreach volume (3–5/wk), booked interviews (1–3/wk), and 100% follow-up completion.
   "Actions Required Today" Engine: Smart action queue that surfaces contacts requiring a 3B7 nudge, pivot message, or post-interview thank you note.
   Campaign Velocity Chart: Visual trends powered by Chart.js comparing messages sent against booked interviews over a 5-week window.
2. 6-Stage Pipeline Kanban Board
   Visual Lifecycle Tracking: Drag-and-drop or click to advance contacts through linear stages:
   Identified ➔ 2. Messaged ➔ 3. Awaiting Reply ➔ 4. Interview Scheduled ➔ 5. Follow-up Pending ➔ 6. Advocate / Nurture
   Real-time Filters: Search by name, company, role, or filter by source tags (AI Innovators List, Conferences, Cold LinkedIn, Mutual Connections).
3. Dynamic Template Quick-Launcher
   Variable Filler: Instantly populates personalized email templates with target name, company, and specific research topics.
   Pre-Built Strategy Templates:
     Initial Value-Add Outreach
     3B7 Low-Friction Nudge (Day +3)
     3B7 Pivot & Graceful Closure (Day +7)
     Post-Interview Thank You (<24 Hours)
     Monthly Advocate Touchpoint
   One-Click Clipboard Copying: Smooth copy-paste workflow into Gmail/Outlook.
4. Contacts Directory & Interaction Timeline
   Full searchable table view for managing all background research notes, LinkedIn links, and source categories.
   Detailed modal drawer with chronological interaction logs for tracking past emails and call summaries.
5. Integrated TIARA Playbook
   On-demand reference guide for preparing and leading 20-minute informational chats with industry experts.
Tech Stack
    Frontend: HTML5, Modern Vanilla JavaScript (ES6+)
    Styling: Tailwind CSS (via CDN)
    Icons: FontAwesome 6
    Charts: Chart.js
    Data Persistence: Browser localStorage (100% private & client-side)
Quick Start
  Since the application is fully self-contained in a single HTML file, no node_modules or build step is required!
Option 1: Local Setup
  Clone the repository:git clone https://github.com/your-username/outreach_dashboard.git
  Open app.html in any modern web browser (Chrome, Firefox, Safari, Edge).

Option 2: Deploy to GitHub Pages
  Go to your repository Settings > Pages.
  Set the branch source to main (or master) and folder to / (root).
  Save, and your CRM will be live at https://your-username.github.io/outreach_dashboard/app.html!
  
  Built-In Methodologies
    The 3B7 Follow-Up Rule
      Day +3 Business Days: Send a short, low-friction reminder ("Quick follow-up...").
      Day +7 Business Days: Pivot the angle or offer a value-add link, then gracefully archive to prevent inbox clutter.
    The TIARA Informational Interview Framework
      Trends: Macro shifts in the AI/ML domain over the next 6–12 months.
      Insights: Non-obvious takeaways from scaling or deploying models.
      Advice: Specific skill sets or domain knowledge to prioritize.
      Resources: Essential research papers, repos, or benchmarks.
      Assignments: High-impact projects and secondary network connections.
      
      License
      Distributed under the MIT License. See LICENSE for more information.
