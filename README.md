MAHI (MindSync – Real-Time Collaborative Knowledge Map) is inspired by the legendary Mahendra Singh Dhoni (MSD) — a symbol of calmness, clarity, and strategic brilliance.

Just like Dhoni leads with composure and vision, Mahi helps you think, plan, and create with focus. It’s a space where ideas flow like Dhoni’s decisions on the field — smart, precise, and impactful.

Built for thinkers, learners, and teams, Mahi lets you visualize your thoughts as connected nodes, collaborate in real time, and turn scattered ideas into structured knowledge.

With Mahi, you don’t just draw a map — you build your mindset, one node at a time.
🎯 Core Features
1. Landing Page

Clean hero section introducing MindSync.

Buttons: Get Started, Sign In, Sign Up.

Visual preview of a glowing knowledge map in the background.

2. User Authentication

Signup/Login/Logout with JWT tokens.

Profile page where users manage their data.

Secure password handling.

3. Dashboard

Displays all maps a user has created.

Buttons:

Create New Map

Open Map

Delete Map

Public vs private maps toggle.

4. Mind Map Editor

Built using React + D3.js (or React Flow) for interactive graph visualization.

Core actions:

Add Node → create a new draggable bubble.

Link Node → connect two bubbles with a glowing line.

Delete Node → remove nodes and their edges.

Save Graph → persist to database.

Export Graph → download as PNG or PDF.

Dark Mode → neon glowing cyberpunk theme.

Smooth animations, zooming, panning, and responsive UI.

5. Collaboration

Real-time editing with WebSockets or Supabase Realtime.

Show colored cursors for each collaborator.

Changes sync instantly for all users (like Google Docs but with mind maps).

6. AI Integration

When adding a node, the system suggests related ideas.

Example: If you add Machine Learning, AI may suggest Neural Networks or Data Science.

Suggested nodes appear as ghost bubbles with an Accept button.

7. Database

Use Supabase (preferred) or Firebase.

Store:

User profiles.

Graph data (nodes + edges).

Collaboration rooms.

Support for real-time updates.

8. Other Features

Gamification – badges for milestones (10 nodes created, 5 maps shared, etc.).

Search & Filter – quickly find nodes inside large maps.

Offline-first support (PWA) – users can open and edit maps even offline.

Exportable Graphs – share maps in PDF/PNG.

Mobile Friendly – works smoothly on both phone and desktop.

⚙️ Tech Stack

Frontend:

React + TailwindCSS (UI & styling)

D3.js or React Flow (graph visualization)

Framer Motion (animations)

Backend:

Node.js + Express

WebSockets for real-time sync

Database:

Supabase (authentication, storage, real-time features)

Alternative: Firebase

AI (basic):

Local NLP keyword matching

Optional HuggingFace API for advanced suggestions

🚀 Why It’s Special

Not just another CRUD app → it’s visual, collaborative, and AI-assisted.

Useful for:

Students (study maps, notes, revision).

Teams (brainstorming, planning).

Researchers (organizing knowledge).

Cyberpunk-styled UI makes it engaging and futuristic.
