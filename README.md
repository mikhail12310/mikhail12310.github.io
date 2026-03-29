# Mikhail Joseph Chakramakkil - Personal Portfolio

A premium, cinematic personal portfolio built to showcase experience in Data Science, Machine Learning, and Agentic AI. This project uses static HTML, CSS, and vanilla JavaScript and is fully compatible with GitHub Pages.

## 🚀 Live Demo
Once deployed to GitHub Pages, your site will be available at your repository's `.github.io` URL (e.g., `https://mikhail12310.github.io`).

## 📂 Project Structure
```text
.
├── index.html          # Home page detailing high-level overviews and featured work.
├── about.html          # Bio, skills, and background narrative.
├── projects.html       # Detailed project cards and highlighted GitHub repos.
├── experience.html     # Professional experience and education timeline.
├── assets/
│   ├── css/
│   │   └── style.css   # Main design system, dark mode variables, and animations.
│   ├── js/
│   │   └── main.js     # JavaScript for scroll-reveals, responsive nav, and interactions.
│   └── images/
│       └── profile.jpg # Profile photo used across the site.
├── files/
│   └── Resume.pdf      # Downloadable resume document.
└── knowledge/          # Original reference materials and unstructured content.
```

## 🛠 Deploying to GitHub Pages
Because this site uses zero build tools and perfectly standard HTML/CSS/JS, deploying is virtually instant:
1. Commit all files to the `main` branch of this repository.
2. Go to your repository settings on GitHub.
3. Navigate to **Pages** in the left sidebar.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select `main` (or `master`) as your branch and click **Save**.

## 🎨 Customizing Styles & Content
- **Colors & Typography**: To adjust the color scheme, edit the CSS variables in the `:root` pseudo-class inside `assets/css/style.css`.
- **Replacing the Photo**: Replace `assets/images/profile.jpg` with a new image ensuring it is of high quality.
- **Updating the Resume**: Replace `files/Resume.pdf` with your latest resume version to keep the download link functional.
- **Projects**: To add more projects, copy the HTML block of an existing `<div class="project-card">` or `<a class="mini-card">` inside `projects.html` and update its content and tags.

## ✨ Features
- **Dark Mode First**: Engineered with a deep palette and soft glows optimized for a premium viewing experience.
- **Performance Optimized**: Vanilla JS ensuring rapid load times with smooth `IntersectionObserver` scroll-reveals.
- **Responsive Navigation**: Retains usability across mobile devices with a custom hamburger menu.
- **Interaction Design**: Includes subtle hover-lift mechanics and a specialized gradient mouse-tracking effect on complex cards.
