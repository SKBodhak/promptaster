<div align="center">
  
  # 🌌 Prompt Nova
  *A Futuristic, Serverless Prompt Library & Management System*

  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
  [![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](#)
  [![GitHub API](https://img.shields.io/badge/GitHub_API-181717?style=for-the-badge&logo=github&logoColor=white)](#)

</div>

<br>

## 🚀 Overview

**Prompt Nova** is a fully dynamic, single-page application (SPA) designed to curate, share, and manage AI prompt formulas. Built with a sleek, aesthetic "Glassmorphism" UI and powered entirely by the **GitHub REST API**, it operates seamlessly without traditional backend servers or databases.

## ✨ Key Features

### 💻 User Interface (Front-End)
* **Immersive Gallery Views:** Toggle between Grid, Card, and Detail views.
* **Auto-Swiping Carousels:** Image carousels for prompt previews that auto-play smoothly.
* **Smart Search & Filters:** Instantly filter prompts by categories (Anime, Sci-Fi, Realistic, 3D Render, etc.).
* **Custom Authentication:** In-house user registration with strict validation, password strength checking, and recovery token generation.
* **Local Saves:** Users can 'Save' their favorite prompts directly to their browser's local storage.
* **Dynamic Modals & Toasts:** Beautiful, haptic-enabled UI interactions.

### 🛡️ Master Admin Panel
* **Live Dashboard:** Control every aspect of the site without touching the code.
* **Instant Sync:** Edit Site Configurations, UI Texts, and Developer Profiles, syncing instantly to live JSON files via GitHub API.
* **Submission Queue:** Review, approve, or reject user-submitted prompts.
* **Alert Management:** Create and push global top-banners and center popups to live users.
* **User & Inbox Management:** View registered users, manage security, and read direct messages.

---

## 🏗️ Architecture: GitHub as a Database

Prompt Nova uses a highly unique, lightweight architecture. Instead of Firebase or SQL, all dynamic data is stored securely in structured `JSON` files directly within this repository. The application uses GitHub Personal Access Tokens (PAT) to execute read/write operations seamlessly.

**Core Data Files:**
* `site.json` - Global UI and branding configurations.
* `system.json` - Feature toggles and menu structures.
* `ui_texts.json` - Dynamic button and navigation texts.
* `developer.json` - Developer profile and social links.
* `alerts.json` - Active banners and modal popups.
* `data.json` - The live library of approved prompts.
* `create.json` - Pending prompt submissions.
* `users.json` - Encrypted user database.
* `messages.json` - User inbox and direct messages.

---

## ⚙️ Setup & Installation

To deploy your own instance of Prompt Nova:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/SKBodhak/PromptNova.git](https://github.com/SKBodhak/PromptNova.git)