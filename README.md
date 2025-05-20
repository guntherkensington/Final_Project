
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
