# WebSkills Website

A modern, responsive website built using HTML and CSS. It is designed to showcase web development skills with clean UI, smooth navigation, and mobile-friendly components.

## Features

- Fixed navigation bar with smooth scrolling
- Multiple content cards with flexible layouts
- Responsive design with Flexbox
- Styled FAQ accordion using <details> and <summary>
- Contact form section with styled inputs
- Clean, modern footer design

## Sections Overview

1. **Home** – Hero card with CTA
2. **About** – Informative text with supporting image
3. **Services / Lessons** – Feature cards highlighting different offerings
4. **Partners** – Visual showcase
5. **FAQ** – Interactive questions section
6. **Contact** – Form for user inquiries
7. **Footer** – Navigation and quick info

## Tech Stack

- HTML5
- CSS3 (Flexbox, scroll-behavior, custom styling)

## Setup

Just clone the repo and open `index.html` in your browser:

```bash
git clone https://github.com/yourusername/webskills-site.git
cd webskills-site
```

Open `index.html` with any browser.

## Contributing

Feel free to fork this project, open issues, or make pull requests. It's designed to grow.

## License

This project is open-source and available under the MIT License.


# Final Project Setup using Termux

## Step-by-Step Guide

### 1. Open Termux

### 2. Change Repositories
```bash
termux-change-repo
```

### 3. Update and Upgrade Packages
```bash
pkg update && pkg upgrade
```

### 4. Grant Storage Permissions
```bash
termux-setup-storage
```

### 5. Install Node.js
```bash
pkg install nodejs
```

### 6. Install Live Server Globally
```bash
npm install -g live-server
```

---

## Create Project Structure

### 7. Navigate to Home
```bash
cd
```

### 8. Create Project Folder
```bash
mkdir Final_Project && cd Final_Project
```

### 9. Create Subfolders
```bash
mkdir css js assets
```

### 10. Add Files with Code

#### HTML
```bash
cat > index.html
```
*Paste your HTML code, then press `CTRL + D`*

#### README
```bash
cat > README.md
```
*Paste content, then press `CTRL + D`*

#### CSS
```bash
cat > css/style.css
```
*Paste CSS, then `CTRL + D`*

#### JavaScript
```bash
cat > js/script.js
```
*Paste JS code, then `CTRL + D`*

---

## Move and Run

### 11. Move Project to Documents
```bash
cd && mv Final_Project storage/shared/documents
```

### 12. Navigate and Run Server
```bash
cd storage/shared/documents/Final_Project
live-server
```
