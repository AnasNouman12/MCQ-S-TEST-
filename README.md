<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/AnasNouman12/MCQ-TEST">
    <img src="https://raw.githubusercontent.com/AnasNouman12/MCQ-TEST/main/public/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h1 align="center">🎓 MCQ'S TEST</h1>
  <p align="center">
    A Secure, AI‑Proctored Online Examination Platform<br/>
    <a href="https://github.com/AnasNouman12/MCQ-TEST"><strong>Explore the docs »</strong></a>
    ·
    <a href="https://github.com/AnasNouman12/MCQ-TEST/issues">Report Bug</a>
    ·
    <a href="https://github.com/AnasNouman12/MCQ-TEST/issues">Request Feature</a>
  </p>
</div>

<!-- BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/status-active-brightgreen?style=flat-square" alt="Project Status: Active">
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="License: MIT">
  <img src="https://img.shields.io/github/stars/AnasNouman12/MCQ-TEST?style=flat-square" alt="GitHub stars">
  <img src="https://img.shields.io/github/issues/AnasNouman12/MCQ-TEST?style=flat-square" alt="GitHub issues">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

---

## 💡 About the Project

**MCQ’S TEST** is a lightweight, high‑performance Single Page Application (SPA) designed to administer automated multiple‑choice examinations. With an integrated secure execution environment, the platform requires **zero backend infrastructure** and runs entirely in the browser using robust in‑memory state management.

Built for institutions and educators, it offers a complete examination lifecycle:
- **Admin Dashboard** for test creation, token‑based student enrollment, and result moderation.
- **Student Portal** with a distraction‑free exam experience and a clear result view.
- **Real‑time AI Proctoring** to ensure academic integrity without any server‑side complexity.

---

## 🔐 Live Demo Credentials

Test the platform immediately using the built‑in mock database:

| Role      | Email                  | Password   |
|-----------|------------------------|------------|
| **Admin** | admin@mcqstest.com     | admin      |
| **Student** | john@example.com      | password   |

---

## 🌟 Core Features

### 🛡️ Strict Anti‑Cheat Proctoring
- **Hardware Validation** – Enforces camera and microphone permissions before the exam begins.
- **Fullscreen Execution** – Locks the test environment; exiting fullscreen logs a security violation.
- **Action Restrictions** – Disables right‑click, copy/paste, and developer shortcuts (e.g., F12, Ctrl+C).
- **Visibility & Network Tracking** – Monitors tab‑switching and offline events, automatically submitting the exam on network loss.

### 👨‍💼 Admin Dashboard
- **Token‑Based Registration** – Generate secure, single‑use tokens (`MCQ-2026-XXXXXX`) for controlled student onboarding.
- **Rapid Test Builder** – Create exams with custom duration, passing marks, and assigned students.
- **Bulk Text Importer** – Paste unformatted question blocks to automatically parse and populate an exam.
- **Live Moderation** – Review automatic grading, proctoring alerts, and publish final results.

### 🎓 Student Experience
- **Clean Interface** – Distraction‑free environment with a live countdown timer.
- **Smart Navigation** – Visual question palette showing answered, flagged for review, and unvisited questions.
- **Instant Feedback** – Graded results and pass/fail status visible immediately after the admin publishes them.

---

## 🚀 Deployment

This application is a **standalone HTML file** – deployment is instant and cost‑free.

1. **Download** the source code and save it as `index.html`.
2. **Upload** the file to any static hosting provider:
   - GitHub Pages
   - Vercel
   - Netlify
   - Cloudflare Pages
3. (Optional) Connect a custom domain in your hosting dashboard.

Your examination platform is now live globally.

---

## 🏗️ Architecture & Tech Stack

| Category           | Technology / Approach                                    |
|--------------------|----------------------------------------------------------|
| **Frontend**       | Vanilla JavaScript (ES6+), HTML5                         |
| **Styling**        | Tailwind CSS (via CDN)                                   |
| **Icons**          | Lucide Icons                                             |
| **State Management** | Custom `appState` object handling relational data (Users, Tokens, Tests, Attempts) entirely in memory. |
| **Proctoring Engine** | Built‑in DOM event listeners + browser APIs (Fullscreen, Visibility, Network) |

No frameworks, no build steps – just a single, self‑contained HTML document.

---

## 👨‍💻 Author

**Anas Nouman**  
*Generative AI Engineer & AI‑Powered Web Developer*

- **GitHub:** [@AnasNouman12](https://github.com/AnasNouman12)
- **Email:** [anislund@gmail.com](mailto:anislund@gmail.com)
- **Project Ecosystem:** X‑NOMI Workspace

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## ⭐ Support

If you find this project helpful, please consider giving it a ⭐ on GitHub – it helps more than you think!

---

<p align="center">Made with ❤️ by Anas Nouman</p>
