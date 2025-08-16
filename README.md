# 🍲 Recipe Book
A simple and elegant website for saving and browsing recipes, built with **HTML, CSS, and JavaScript**. The project is lightweight, easy to understand, and has a clear structure for customization.

## 📖 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running Locally](#running-locally)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Deploy on GitHub Pages](#deploy-on-github-pages)

## 🔎 Introduction
**Recipe Book** is a static website for storing and organizing cooking recipes. It’s beginner-friendly and perfect for learning the basics of web development or creating your own online recipe collection.

## ✨ Features
- 📱 **Responsive design** — works on phones and desktops  
- 🍴 **Easy recipe browsing** — each recipe has its own page  
- 🎨 **Modular styles** — component-based CSS for consistency  
- ⚡ **Fast & lightweight** — static files only, no backend required  
- 🛠️ **Simple structure** — easy to expand with more recipes

## 🌍 Demo
*(Optional: add a link if you deploy it on GitHub Pages, Netlify, or Vercel)*  
Example: [Live Demo](https://texkill.github.io/recipe-book)

## 📂 Project Structure
```text
recipe-book/
├── assets/              # Images, icons, fonts
├── components-css/      # CSS styles for reusable components
├── components/          # Reusable HTML/JS components
├── pages-css/           # Page-specific styles
├── pages/               # Individual recipe HTML pages
├── index.html           # Homepage
├── style.css            # Global stylesheet
└── README.md            # Documentation
```
[The Markup](https://www.figma.com/design/XEpPYOTStdhn6rpfVGqv9q/Web-recipe-book--Community-?node-id=153-4483&t=KRmGjVWzhcfTL1rD-0)

## 🚀 Getting Started

### ✅ Prerequisites
- Any modern browser (Chrome, Firefox, Edge, etc.)  
- (Optional) [Node.js](https://nodejs.org/) if you want to run a local development server

### 📥 Installation
```bash
git clone https://github.com/TexKill/recipe-book.git
cd recipe-book
```
*(Optional) Install dependencies if you add build tools later:*
```bash
npm install
```

### ▶️ Running Locally
- Open `index.html` directly in your browser  
**or**  
- Start a local live server (recommended for development):
```bash
npx live-server
```

## 🖥️ Usage
- To add a new recipe:  
  1. Create a new HTML file in `pages/`  
  2. Add custom styles in `pages-css/`  
  3. Add a link to the recipe in `index.html`  
- Edit **global styles** in `style.css`  
- Reuse **components** from `components/` and `components-css/`

## 🤝 Contributing
Contributions are welcome! 🎉  
1. Fork the repository  
2. Create a new branch:
   ```bash
   git checkout -b feature/my-feature
   ```
3. Commit changes:
   ```bash
   git commit -m "Add new recipe"
   ```
4. Push your branch:
   ```bash
   git push origin feature/my-feature
   ```
5. Open a Pull Request

## 📜 License
This project is licensed under the **MIT License**. You are free to use, modify, and share it.

👨‍💻 Author: [TexKill](https://github.com/TexKill)

## 🚀 Deploy on GitHub Pages
You can easily publish this project online with GitHub Pages:

1. Go to your repository on GitHub  
2. Open **Settings** → **Pages**  
3. Under **Source**, select the `main` branch and the `/ (root)` folder  
4. Click **Save**  
5. Your site will be available at:
   ```
   https://TexKill.github.io/recipe-book
   ```
   *(Replace `your-username` with your GitHub username.)*
