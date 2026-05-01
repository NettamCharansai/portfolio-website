#  Portfolio Website – Nettam Charan Sai

A modern, responsive portfolio website built using React.js and Material UI to showcase my work in **backend systems, distributed applications, and performance-focused engineering projects**.

---

##  Overview

This portfolio serves as a centralized platform to highlight:

* Engineering projects (SRE / Backend focused)
* Technical skills and tools
* Professional experience and achievements
* Coding profiles and contact information

Designed with simplicity and performance in mind, the site ensures a smooth user experience across devices.

---

##  Live Demo

https://nettamcharansai.github.io/portfolio-website/ (GitHub Pages)

---

##  Architecture & Deployment

```text id="s66z8o"
                ┌──────────────────────────┐
                │      User Browser        │
                └──────────┬───────────────┘
                           │ HTTP Request
                           ▼
                ┌──────────────────────────┐
                │   React Frontend (SPA)   │
                │   Material UI Components │
                └──────────┬───────────────┘
                           │
                           ▼
                ┌──────────────────────────┐
                │  Static Hosting Layer    │
                │   (GitHub Pages)         │
                └──────────┬───────────────┘
                           │
                           ▼
                ┌──────────────────────────┐
                │  CI/CD Pipeline          │
                │ (GitHub Actions)         │
                └──────────────────────────┘
```

---

##  Data Flow

### 1. User Access

* User visits the portfolio via browser

---

### 2. Static Asset Delivery

* GitHub Pages serves:

  * HTML
  * CSS
  * JavaScript bundles

---

### 3. React Rendering

* React loads components dynamically
* Material UI renders responsive layout

---

### 4. Navigation

* Client-side routing ensures fast transitions between sections:

  * About
  * Projects
  * Experience
  * Contact

---

### 5. External Integrations

* Links to:

  * GitHub repositories
  * LeetCode profile
  * Email / LinkedIn

---

##  Tech Stack

| Category     | Technology     |
| ------------ | -------------- |
| Frontend     | React.js       |
| UI Framework | Material UI    |
| Deployment   | GitHub Pages   |
| CI/CD        | GitHub Actions |

---

##  Features

* Responsive design (mobile + desktop)
* Clean and minimal UI
* Project showcase with GitHub integration
* Fast static deployment
* Automated deployment pipeline using GitHub Actions

---

##  Project Structure

```bash id="5czd3z"
portfolio-website/
│
├── public/        # Static assets
├── src/           # React components and logic
├── .github/       # GitHub Actions workflow
├── package.json   # Dependencies and scripts
└── README.md
```

---

##  Installation & Setup

### 1. Clone Repository

```bash id="53fbnf"
git clone https://github.com/NettamCharansai/portfolio-website.git
cd portfolio-website
```

---

### 2. Install Dependencies

```bash id="g0hg1h"
npm install
# or
yarn
```

---

### 3. Run Development Server

```bash id="t9nyyk"
npm start
# or
yarn start
```

---

### 4. Build for Production

```bash id="gjs81o"
npm run build
```

---

##  CI/CD Pipeline

This project uses GitHub Actions to:

* Build the React application
* Deploy automatically to GitHub Pages

Every push to the main branch triggers deployment.

---

##  Purpose

This portfolio is designed to:

* Showcase **engineering-focused projects**
* Highlight **system design and backend capabilities**
* Serve as a professional entry point for recruiters and collaborators

---

##  Future Improvements

* Add project architecture visualizations
* Improve performance optimization (lazy loading, caching)
* Integrate analytics for usage tracking

---

##  Author

**Nettam Charan Sai**

* GitHub: [https://github.com/NettamCharansai](https://github.com/NettamCharansai)
* LeetCode: [https://leetcode.com/u/CharanSai1/](https://leetcode.com/u/CharanSai1/)

---

##  License

MIT License

---


