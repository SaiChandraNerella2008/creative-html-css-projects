# Creative HTML & CSS Webpage Projects

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive Design](https://img.shields.io/badge/Responsive-Mobile%20%7C%20Tablet%20%7C%20Desktop-success?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

**A collection of responsive, production-ready frontend web projects demonstrating modern HTML5 semantics, modular CSS3 layouts (Flexbox & Grid), interactive elements, and accessible UX.**

[Explore Projects](#-selected-projects) • [Live Demos](#-how-to-preview-locally) • [Project Structure](#-repository-structure) • [License](#-license)

</div>

---

## 📌 Assignment Context

> **Task**: Build assigned webpages using HTML and CSS. Decide the layout, colors, typography, images, and overall visual design. The webpage should be organized, attractive, and responsive across desktop, tablet, and mobile screens.

This repository features **three standout projects**, curated one each from **Group 1**, **Group 2**, and **Group 3**:

| Group | Project Number | Project Title | Key Highlights | Folder |
| :---: | :---: | :--- | :--- | :--- |
| **Group 1** | **Project 1** | **Personal Student Portfolio** | Profile, skills, projects, achievements, contact form | [`01-personal-portfolio/`](./01-personal-portfolio/) |
| **Group 2** | **Project 8** | **QuickBite Food Delivery** | Restaurant cards, categories, popular dishes, discount coupons, order buttons | [`02-food-delivery-website/`](./02-food-delivery-website/) |
| **Group 3** | **Project 7** | **Synthetix AI Technology** | Foundation AI products, SMoE architecture, feature grid, industry apps, team, sandbox API form | [`03-ai-technology-website/`](./03-ai-technology-website/) |

---

## 🌟 Selected Projects

### 1. 🎓 Personal Portfolio Website (`Group 1 - Project 1`)
> *Create a personal portfolio webpage for a student with a profile, skills, projects, achievements, and contact section.*

- **Design Philosophy**: Minimalist, professional, and accessible. Uses high-contrast typography and subtle indigo gradients.
- **Key Sections**:
  - **Hero**: Profile card with live metrics (15+ Projects, 400+ Problems Solved), social media integrations, and internship status badge.
  - **About & Education**: B.Tech in CSE background timeline and core technical competencies.
  - **Categorized Skills**: Chip tags for Frontend, Programming Languages, Backend, and Developer Tools.
  - **Project Showcase**: Visual cards with tag pills, preview images, and external repository links.
  - **Achievements & Certifications**: Hackathon top finishes, Dean's merit list, and competitive programming milestones.
  - **Interactive Contact Form**: Complete with validation and direct communication links.
- **Directory**: [`01-personal-portfolio/`](./01-personal-portfolio/)

---

### 2. 🍔 QuickBite - Food Delivery Website (`Group 2 - Project 8`)
> *Create a food-delivery webpage with restaurant cards, food categories, popular dishes, offers, prices, and order buttons.*

- **Design Philosophy**: Warm, vibrant, appetizing UI with amber/orange branding (`#ff5722`), floating notification pills, and interactive shopping cart state.
- **Key Sections**:
  - **Hero & Search**: 30-minute delivery guarantee pill, dish search bar, and floating delivery dispatch badges.
  - **Categories**: Icon cards for Burgers, Artisan Pizza, Sushi, Healthy Bowls, Tacos, and Desserts.
  - **Special Offers**: Promotional coupon banners with discount codes (`COMBOFREE`, `FREEDELIV`).
  - **Partner Restaurants**: Rating badges, distance tracking, cuisine classifications, and delivery times.
  - **Popular Dishes**: High-resolution dish imagery, calorie/diet tags (Veg, Non-Veg, Healthy), current/original prices, and one-click "Add to Cart" buttons.
  - **Social Proof & Mobile App**: 5-star customer testimonials and iOS/Android app store banners.
- **Directory**: [`02-food-delivery-website/`](./02-food-delivery-website/)

---

### 3. ⚡ Synthetix AI - Frontier Intelligence (`Group 3 - Project 7`)
> *Create a modern AI-company webpage showcasing AI products, features, applications, technology information, team members, and a contact section.*

- **Design Philosophy**: Cutting-edge cyberpunk/futuristic dark theme (`#07090e`), neon cyan and violet gradients, glassmorphism cards, and embedded developer code terminal.
- **Key Sections**:
  - **Hero & Code Terminal**: Live Python SDK streaming inference snippet (`synthetix-inference-stream.py`) and global metric counters.
  - **Flagship Products**: Cards for *OmniLLM 4.0* (Reasoning), *VisionNova Neural* (4K Spatial Vision), and *VoiceFlow Ultra* (Sub-50ms Speech).
  - **Platform Features**: Distributed GPU Cloud, Zero-Knowledge confidential computing, Real-time Streaming API, LoRA Fine-Tuning.
  - **Industry Applications**: Industrial Robotics, Medical CT/MRI Imaging Diagnostics, and Algorithmic Quantitative Finance.
  - **Architecture Breakdown**: Sparse Mixture-of-Experts (SMoE) visual token routing diagram.
  - **Research Pioneers**: Profiles of CEO, VP of Neural Architecture, and Head of AI Safety.
  - **Enterprise Sandbox Request**: Interactive API key provision request form.
- **Directory**: [`03-ai-technology-website/`](./03-ai-technology-website/)

---

## 📂 Repository Structure

```text
creative-html-css-projects/
├── README.md                          # Main repository documentation & overview
├── LICENSE                            # MIT License
│
├── 01-personal-portfolio/             # Group 1, Project 1
│   ├── index.html                     # Semantic HTML5 markup
│   ├── style.css                      # Modern CSS3 stylesheet
│   └── README.md                      # Project-specific documentation
│
├── 02-food-delivery-website/          # Group 2, Project 8
│   ├── index.html                     # Semantic HTML5 markup
│   ├── style.css                      # Warm & appetizing CSS3 stylesheet
│   └── README.md                      # Project-specific documentation
│
└── 03-ai-technology-website/          # Group 3, Project 7
    ├── index.html                     # Semantic HTML5 markup
    ├── style.css                      # Futuristic dark-mode CSS3 stylesheet
    └── README.md                      # Project-specific documentation
```

---

## 💻 Tech Stack & Design Standards

- **Markup**: Pure HTML5 (Semantic elements: `header`, `nav`, `main`, `section`, `article`, `figure`, `footer`)
- **Styling**: Pure CSS3 (CSS Custom Properties / Variables, Flexbox, CSS Grid, Transitions, Keyframe Animations)
- **Icons**: Font Awesome 6.4 Free
- **Typography**: Google Fonts (`Plus Jakarta Sans`, `Space Grotesk`, `Outfit`, `Inter`, `Fira Code`)
- **Images**: Unsplash High-Definition Royalty-Free Photography
- **Responsiveness**: Fully responsive with fluid breakpoints (`1200px`, `992px`, `768px`, `480px`)

---

## 🚀 How to Preview Locally

### Option 1: Direct File Opening
Double-click `index.html` inside any of the project folders to open it immediately in your default web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local Python Server (Recommended)
From the root repository folder, run:
```bash
python -m http.server 8000
```
Then navigate to:
- **Project 1 (Portfolio)**: `http://localhost:8000/01-personal-portfolio/`
- **Project 2 (QuickBite)**: `http://localhost:8000/02-food-delivery-website/`
- **Project 3 (Synthetix AI)**: `http://localhost:8000/03-ai-technology-website/`

---

## 🌐 Deploying to GitHub Pages

To host these projects live online using GitHub Pages:

1. Push this repository to GitHub.
2. In your GitHub repository, go to **Settings** > **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` and root `/`.
4. Click **Save**. Within 1–2 minutes, your projects will be live!

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE) - feel free to use and adapt it for learning and portfolio purposes.

---

<div align="center">
Built with ❤️ by <strong>Sai Chandra Nerella</strong>
</div>
