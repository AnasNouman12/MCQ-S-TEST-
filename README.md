Here is a highly polished, open-source-style README.md complete with badges, a cleaner structure, and a professional developer profile block ready for your repository.

🎓 MCQ'S TEST
A Secure, AI-Proctored Online Examination Platform

A lightweight, high-performance single-page application (SPA) designed to administer automated multiple-choice tests to students. Built with an integrated secure execution environment, this platform requires zero backend infrastructure and runs entirely in the browser using robust in-memory state management.

⚡ Live Demo Credentials
Test the platform immediately using the built-in mock database:

Admin Access

Username/Email: admin@mcqstest.com[cite: 1]

Password: admin[cite: 1]

Student Access

Username/Email: john@example.com

Password: password

🌟 Core Features
🛡️ Strict Anti-Cheat Proctoring
Hardware Validation: Enforces camera and microphone permissions prior to exam initiation[cite: 1].

Fullscreen Execution: Locks the exam environment; exiting fullscreen automatically logs a security violation[cite: 1].

Action Restrictions: Disables right-click, copy/paste operations, and keyboard shortcuts (e.g., F12, Ctrl+C)[cite: 1].

Visibility & Network Tracking: Monitors tab-switching and network connectivity, auto-submitting if the user goes offline.

👨‍💼 Admin Dashboard
Token-Based Registration: Generate secure, single-use access tokens (MCQ-2026-XXXXXX) for secure student onboarding.

Rapid Test Builder: Create comprehensive exams with custom parameters (duration, passing marks, assigned students).

Bulk Text Importer: Paste unformatted question blocks to automatically parse and populate exams.

Live Moderation: Review automated grading, proctoring alerts, and publish results instantly.

🎓 Student Experience
Clean Interface: Distraction-free exam environment with a live countdown timer.

Smart Navigation: Visual question palette to track answered, marked-for-review, and unvisited questions.

Instant Feedback: View graded results and pass/fail status immediately after the admin publishes them.

🚀 Deployment
This application operates as a standalone HTML file, making deployment instant and cost-free.

Save the source code as index.html.

Upload the file to any static hosting provider (e.g., GitHub Pages, Vercel, Netlify, or Cloudflare Pages).

Connect your custom domain in the host's dashboard. Your platform is now live globally.

🏗️ Architecture & Stack
Frontend: Vanilla JavaScript (ES6+), HTML5.

Styling: Tailwind CSS (via CDN).

Iconography: Lucide Icons.

State Management: Custom appState object handling complex relational data (Users, Tokens, Assessments, Analytics) entirely in memory.

👨‍💻 Author
Anas Nouman

Generative AI Engineer & AI-Powered Web Developer

GitHub: @AnasNouman12

Email: anislund@gmail.com

Project: X-NOMI Workspace ecosystem

If you find this project helpful, please consider giving it a ⭐ on GitHub!
