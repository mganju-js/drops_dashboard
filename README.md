# Pretzelized Promotion Performance Dashboard

An executive-level dashboard analyzing the performance of the pretzelized product promotion compared to previous campaigns.

## 🚀 Quick Setup Guide

### Step 1: Create GitHub Repository
1. Go to [GitHub](https://github.com) and log in
2. Click the "+" icon in the top right → "New repository"
3. Name it: `pretzelized-dashboard` (or any name you prefer)
4. Make it **Public** (required for free GitHub Pages)
5. **DO NOT** initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Upload Files to GitHub
After creating the repository, GitHub will show you commands. Use these:

```bash
# Navigate to your project folder (where you extracted the files)
cd pretzelized-dashboard

# Add all files
git add .

# Commit the files
git commit -m "Initial dashboard setup"

# Connect to your GitHub repo (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/pretzelized-dashboard.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Click **Pages** in the left sidebar
4. Under "Source", select **main** branch
5. Click **Save**
6. Wait 1-2 minutes, then refresh the page
7. Your site will be live at: `https://YOUR_USERNAME.github.io/pretzelized-dashboard/`

## 📝 Making Updates

### Easy Method: Edit Directly on GitHub
1. Go to your repository on GitHub
2. Click on `index.html`
3. Click the pencil icon (Edit this file)
4. Make your changes
5. Scroll down and click "Commit changes"
6. Wait 1-2 minutes for changes to deploy

### Advanced Method: Edit Locally
```bash
# Make changes to index.html in your text editor
# Then commit and push:
git add index.html
git commit -m "Updated metrics"
git push
```

## 🎨 What You Can Easily Update

### Key Metrics (Top Cards)
Look for these sections in `index.html`:
- **Overall Post-Drop Repeat Rate**: Line ~60
- **Existing Customer Conversion**: Line ~67

### Key Takeaways
Find the "Key Takeaways" section around line ~45-55

### Product Comparison Stats
Find "La Croix" and "Pretzelized" sections around lines 200-250

### Customer Funnel Numbers
Find "funnel-step" sections around lines 150-180

## 💡 Tips
- Each change auto-deploys in 1-2 minutes
- Use browser "Inspect Element" to test changes locally first
- Keep a backup copy of your HTML before major edits
- Use meaningful commit messages to track changes

## 📧 Questions?
Reach out to the data team for assistance with updates or new analyses.
