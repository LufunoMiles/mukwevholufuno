# 🌿 LUFUNO MUKWEVHO | Software Developer Portfolio

[![Netlify Status](https://img.shields.io/badge/netlify-deployed-brightgreen)](https://mukwevholufuno.netlify.app/)
[![Made with HTML/CSS/JS](https://img.shields.io/badge/made%20with-HTML%2FCSS%2FJS-blue)](#)

> **A modern, interactive portfolio website** for Mukwevho Lufuno – a Computer Science student, front-end developer, and tech entrepreneur from South Africa. The site features an **AI-powered Q&A widget** that answers questions about skills, projects, and background in real time.

![Portfolio Preview](https://mukwevholufuno.netlify.app/img/headset%20-%20img.webp)

---

## ✨ Live Demo

🔗 **Visit the live site:** [https://mukwevholufuno.netlify.app/](https://mukwevholufuno.netlify.app/)

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Installation & Local Setup](#-installation--local-setup)
- [AI Ask Anything Widget](#-ai-ask-anything-widget)
- [Customization Guide](#-customization-guide)
- [Deployment](#-deployment)
- [Contact & Socials](#-contact--socials)
- [License](#-license)

---

## 📖 About the Project

This portfolio serves as a digital resume and interactive hub for **Mukwevho Lufuno** – showcasing:

- Academic journey (BSc Computer Science at University of Venda)
- Professional experience (Midlevel Developer, CEO of Amour Tech)
- Leadership roles (Chairperson at GKSS UNIVEN, GDG Limpopo)
- Featured projects with live demos & source code
- Technical skills (frontend, backend, design)
- A unique **AI Ask Anything widget** that answers user questions intelligently based on portfolio context.

The design follows a **soft green aesthetic** with glassmorphic cards, smooth animations, and a fully responsive layout.

---

## 🚀 Key Features

| Feature | Description |
|---------|-------------|
| 🧠 **AI Q&A Widget** | Ask questions like *"What projects have you built?"* or *"What's your tech stack?"* – get instant contextual answers. |
| 📱 **Fully Responsive** | Works seamlessly on mobile, tablet, and desktop devices. |
| 🎨 **Modern UI/UX** | Glassmorphism cards, animated skill bars, gradient blobs, and micro-interactions. |
| 📂 **Project Showcase** | 4 featured projects with tech badges, live demo links, and GitHub repos. |
| 📬 **Contact Form** | Functional form (backend-ready) with validation and success state. |
| 🧭 **Smooth Navigation** | Fixed navbar with scroll-spy and mobile hamburger menu. |
| ⚡ **Performance Optimized** | Lazy-loaded animations, minimal external dependencies, custom CSS. |

---

## 🛠 Tech Stack

**Frontend**

- HTML5
- CSS3 (Custom properties, Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Google Fonts: *Inter* & *Space Grotesk*

**No frameworks** – pure vanilla implementation for maximum performance and control.

**Hosting**

- Netlify (static site hosting)

**Version Control**

- Git & GitHub

---

## 📁 Project Structure
portfolio/
│
├── index.html # Main HTML document (includes embedded CSS/JS)
├── styles.css # External stylesheet (optional if embedded)
├── script.js # External JavaScript (optional if embedded)
├── README.md # Project documentation
└── assets/
└── img/
└── headset-img.webp # Avatar image

text

> **Note:** The current version has CSS and JavaScript embedded directly in the HTML file for simplicity. You can extract them into separate files if desired.

---

## 🛠 Installation & Local Setup

To run this portfolio locally:

```bash
# 1. Clone the repository
git clone https://github.com/LufunoMiles/portfolio.git

# 2. Navigate to project folder
cd portfolio

# 3. Open index.html in your browser
open index.html   # macOS
start index.html  # Windows
Or use Live Server in VS Code for hot-reloading.

🤖 AI Ask Anything Widget
The most distinctive feature – an intelligent Q&A bot that understands context about Lufuno's portfolio.

How it works
User types a question in the input field.

JavaScript analyzes keywords (e.g., "skills", "projects", "contact").

A predefined response matching the query is returned instantly.

No external API calls – all responses are pre-configured for speed and privacy.

Example Questions & Responses
You ask...	AI responds...
"What is your tech stack?"	💻 I'm proficient in HTML/CSS, JavaScript, React, PHP/MySQL, Python, Git, and UI/UX principles.
"What projects have you built?"	🚀 Featured projects: Text-To-Speech, StudCon, Promodoro Focus Timer, and Student Management System.
"What is your career goal?"	🎯 Career goal: Become a full-stack architect and launch innovative tech startups...
"How can I contact you?"	📬 Reach me at mukwevholufuno458@gmail.com or via LinkedIn/GitHub.
Extending the AI
To add more Q&A pairs, edit the getAIResponse() function in script.js:

javascript
if (q.includes('your_keyword')) {
  return "Your custom response here";
}
🎨 Customization Guide
1. Change Colors
Modify the CSS variables in the :root selector:

css
:root {
  --primary: #22c55e;      /* Main green */
  --primary-light: #4ade80;
  --background: #f8fdf9;   /* Light background */
  --foreground: #1a2e1f;   /* Dark text */
}
2. Update Personal Info
Hero section: Edit name, title, bio text.

About section: Update timeline dates, roles, and descriptions.

Skills: Change percentages in data-level attributes (e.g., data-level="85").

Projects: Replace title, description, badges, and links.

3. Replace Avatar Image
Update the <img> tag inside .avatar-circle:

html
<img src="your-new-image.jpg" alt="Your Name">
4. Contact Form Backend
The form currently uses a front-end only submission. To make it functional, add a backend endpoint (e.g., using Formspree, Netlify Forms, or a custom PHP script):

html
<form id="contactForm" action="https://formspree.io/f/your-endpoint" method="POST">
🌐 Deployment
Deploy to Netlify (Recommended)
Push your code to a GitHub repository.

Log in to Netlify.

Click "New site from Git" → Select your repo.

Build settings: Leave empty (static site).

Publish directory: . (root folder).

Click Deploy.

Your site will be live at https://your-name.netlify.app.

Deploy to Vercel
bash
npm install -g vercel
vercel
Follow the CLI prompts – Vercel will auto-detect static settings.

📬 Contact & Socials
Email: mukwevholufuno458@gmail.com

GitHub: @LufunoMiles

LinkedIn: Mukwevho Lufuno

Company: Amour Tech

📄 License
This project is open source under the MIT License. Feel free to use, modify, and distribute – attribution appreciated but not required.

🙏 Acknowledgements
Google Fonts – Inter & Space Grotesk

Netlify – Free static hosting

Remix Icon (placeholder reference)

Design inspiration from modern glassmorphism portfolios
